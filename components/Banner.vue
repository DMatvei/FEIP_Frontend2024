<template>
  <div class="banner">
    <h1>
      <slot></slot>
    </h1>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="sass">
@use './assets/variables' as var

.banner
  font: 
    family: var.$font-title

  display: flex
  h1
    background: 
      color:  #42ad00
    margin: 0
    padding: 1em
    
</style>