<template>
    <h1>这是首页</h1>
    <TodoList/>
    <Rate :value="3"/>
    <Rate :value="4" theme="red"/>
    <Rate :value="1" theme="green"/>
    <Count/>
</template>
<script setup>
import { ref } from 'vue';
import TodoList from '../components/Todolist.vue';
import Rate from '../components/Rate.vue';
import Count from '../components/Count.vue';
let score = ref(3);
</script>