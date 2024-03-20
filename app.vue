<script setup>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Body from './components/Body.vue';
</script>



<template>
  <NuxtLayout>
    <Header />

    <Body />

    <Footer />
  </NuxtLayout>






</template>

<script lang="ts" setup>

</script>

<style lang="sass">
@use './assets/variables' as var

:root
  font:
    family: var.$font-text
    size: 62.5%
  display: flex
  flex: 
    direction: column
    wrap: nowrap
  


body
  margin: 0
  // display: flex
  flex: 
    // direction: column
    grow: 1
  background-color: #ff8e8e
</style>