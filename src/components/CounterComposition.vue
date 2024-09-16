<template>
<h3>{{ counter }}</h3>
<button @click="addCounter">Incrementar</button>
</template>

<script lang="ts" setup>
import { ref } from 'vue';

let counter = ref(0);
const addCounter = () => {
    counter.value++;
}
// SIN PONER EL setup EN EL SCRIPT
// import {defineComponent,ref} from 'vue';
// export default defineComponent({
//     name : 'counterComposition',
//     setup(){
//         let counter = ref(0);
//         const addCounter = () => {
//             counter.value++;
//         }
//         return {
//             counter,
//             addCounter
//         }
//     }

// });
</script>