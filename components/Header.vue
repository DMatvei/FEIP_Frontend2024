<template>
  <header>
    <h1>Header
    </h1>

  </header>
</template>

<script lang="ts" setup>

</script>

<style lang="sass">

@use './assets/variables' as var


header > h1
  margin:
    top: 0%
  padding:
    top: 1%
    left: 2%
    bottom: 0.5%
  font:
    family: var.$font-title
  color: #ff0000
  background-color: #9ed1d6


</style>