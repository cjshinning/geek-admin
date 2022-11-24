<template>
  <h1>这是首页</h1>
  <TodoList />
  <!-- <Heading num="1"/> -->
  <Heading :level="2">hello geekbang</Heading>
</template>
<script setup>
import {ref} from 'vue';
// import TodoList from "../components/Todolist.vue";
import TodoList from "../components/Todolist.jsx";
// import Heading from "../components/Heading.vue";
import Heading from "../components/Heading.jsx";
</script>