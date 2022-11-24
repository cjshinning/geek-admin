<template>
  <h1 v-if="num==1">标题{{num}}</h1>
  <h2 v-if="num==2">标题{{num}}</h2>
  <h3 v-if="num==3">标题{{num}}</h3>
  <h4 v-if="num==4">标题{{num}}</h4>
  <h5 v-if="num==5">标题{{num}}</h5>
  <h6 v-if="num==6">标题{{num}}</h6>
</template>
<script setup>
import { defineProps } from 'vue'
const props = defineProps({
    num: {
        type: Number,
        required: true
    }
})

console.log(props.num) // [1,2,3,4,5]
</script>