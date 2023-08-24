<template>
    <div>
      <h1>{{ message }}</h1> 
    </div>
  </template>
  
  <script setup>
  import { ref, createApp } from 'vue';
  
  const message = ref('My first VueJS Task');
  const vue_det = createApp({
    data() {
      return {
        message: 'My first VueJS Task'
      };
    }
  })
  
  </script>
  
  
  <style>
  #app {
    text-align: center;
    margin-top: 2rem;
  }
  
  p {
    font-size: 1.5rem;
  }
  
  @media (min-width: 1024px) {
    #app {
      margin-top: 4rem;
    }
  }
  </style>
  
