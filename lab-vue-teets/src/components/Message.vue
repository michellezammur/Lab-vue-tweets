<template>
    <p class="message">
      {{ message }}
    </p>
  </template>
  
  <script setup>
  defineProps({
    message: {
      type: String,
      default: "Some Generic Tweet about a cute dog!",
    },
  });
  
  </script>
    