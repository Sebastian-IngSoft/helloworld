<template>
    <h3>{{ counter }}</h3>
    <button @click="increment">Incrementar</button>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'CounterOption',

    components: {},
    data() {
        return {
            counter : 0
        }
    },

    methods: {
        increment(){
            this.counter++;
        },
    },
});
</script>

<style>

</style>