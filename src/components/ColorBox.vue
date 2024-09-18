<template>
    <div>
      <select v-model="color">
          <option value="red">Red</option>
          <option value="green">Green</option>
          <option value="blue">Blue</option>
      </select>
      <div class="box" :style="{ backgroundColor: color }"></div>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue'
  
  const color = ref('red') // Khởi tạo biến phản ứng cho màu sắc
  </script>
  
  <style scoped>
  .box {
    margin-top: 20px;
    width: 200px;
    height: 200px;
  }
  </style>
  