<template>

<img
        referrerpolicy="no-referrer"
        :src="image"
        className="profile"
        alt="profile"
      />

</template>

<script setup>
  
     const props = defineProps({
      image: {
        type: String,
      }
    })
    
    console.log(props.image)
      </script>




