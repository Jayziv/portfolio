<!-- layouts/default.vue -->

<template>
  <div>
    <navbar/>
    <nuxt/>
    <bottom/>
  </div>
</template>

<script>
  import Navbar from '~/components/Navbar'
  import Bottom from '~/components/Bottom'

export default {

  components:{
    Navbar,
    Bottom
  }
  
}
</script>

<style>
  html {
    font-family: "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
  }
</style>