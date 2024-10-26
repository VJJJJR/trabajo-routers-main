<template>
    <div class="about">
      <h1>This is an about page {{cc != undefined ? cc : 0}}</h1>
    </div>
  </template> 
  <script setup>
defineProps({
cc: Number,

})
</script>
  
