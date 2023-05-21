<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script setup lang="ts">
let arr:[string,number] = ['1',2]
console.log(arr)
</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
