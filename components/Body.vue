<script setup>
  import Card from './Card.vue';
  import Banner from './Banner.vue';


</script>


<template>

  <main>
    <Banner>Banner</Banner>
    <div>

      <h1 class="title">Hellow World! 1</h1>
      <p> Hello world 2</p>
    </div>
    <div class="flexrow">
      <Card> Here </Card>
      <Card> and Here </Card>

    </div>



  </main>
</template>

<script lang="ts" setup>

</script>

<style lang="sass">
@use './assets/variables' as var
@use "./assets/class_style" as cs

.title
  font:
    family: var.$font-title

main
  margin: 
    left: 1%
</style>