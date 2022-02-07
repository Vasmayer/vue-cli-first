<template>
  <div id="app">
   
    <MainTitle />
    <Jumbo />
  </div>
</template>

<script>
import MainTitle from './components/title.vue'
import Jumbo from './components/jumbo.vue'

export default {
  name: 'App',
  components: {
    MainTitle,
    Jumbo
  }
}
</script>

<style>

</style>
