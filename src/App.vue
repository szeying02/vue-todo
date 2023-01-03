<script setup>
import TodoList from './TodoList.vue';
</script>

<template>
    <main>
        <h1> Todo List </h1>
        <TodoList />
    </main>
</template>

<style scoped>
    main {
        font-family: Verdana, sans-serif;
    }

    h1 {
        font-weight: bold; 
        color: white;
        padding: 8px 16px;
        background-color: rgb(57, 57, 57);
        border: solid grey;
        border-radius: 8px;
        margin-bottom: 16px;
        text-align: center;
    }
</style>
