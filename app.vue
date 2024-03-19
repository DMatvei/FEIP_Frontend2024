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


body
  margin: 0
</style>