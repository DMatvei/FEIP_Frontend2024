<template>
  <header>
    <div class="flexrow">
      <div class="startrow">

      </div>
      <div class="endrow">
        <link href="tel:+79009009090"> +7(900)900-90-90 </link>
      </div>


    </div>


  </header>
</template>

<script lang="ts" setup>

</script>

<style lang="sass">

@use './assets/variables' as var
@use 'assets/class_style'


// header > h1
//   margin:
//     top: 0%
//   padding:
//     top: 1%
//     left: 2%
//     bottom: 0.5%
//   font:
//     family: var.$font-title
//   color: #ff0000
  

header
  background-color: #F5F7F3
  padding:
    top: 2.4rem
    bottom: 2.4rem
    left: 8.8rem
    right: 8.8rem
  font: 
    size: 1.4rem


header .flexrow
  justify-content: space-between  
// .endrow
//   display: flex
//   align:
//     content: flex-end

</style>