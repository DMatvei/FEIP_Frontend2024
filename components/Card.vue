<template>
  <div class="card">
      <slot></slot>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="sass">

@use './assets/variables' as var

.card
  font: 
    family: var.$font-title
  background: 
    color: #69d88e
  display: flex
</style>