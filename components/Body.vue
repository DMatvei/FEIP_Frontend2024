<script setup>
  import Card from './Card.vue';


</script>


<template>

  <main>

    <div>

      <h1 class="title">Hellow World! 1</h1>
      <p> Hello world 2</p>
    </div>
    <Card> Here </Card>
    <Card> and Here </Card>


  </main>
</template>

<script lang="ts" setup>

</script>

<style lang="sass">
@use './assets/variables' as var

.title
  font:
    family: var.$font-title

main
  margin: 
    left: 1%
</style>