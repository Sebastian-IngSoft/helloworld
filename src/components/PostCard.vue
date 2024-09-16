<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum exercitationem ex est tempore animi expedita provident sequi pariatur laborum corrupti, amet minus ratione delectus sed distinctio porro voluptatem. Officia, nesciunt?</p>
        <PostButton />
    </div>
</template>

<script lang="ts" setup>
import PostButton from './PostButton.vue';


</script>
<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>