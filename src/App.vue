<template lang="pug">
  #root-app
    MainMenu
    router-view
    Footer
  
</template>

<script>
import MainMenu from './components/General/MainMenu.vue'
import Footer from './components/General/Footer.vue'

export default {
  name: 'app',
  components: {
    MainMenu,
    Footer
  }
}
</script>

<style lang="scss">
*{
  margin:0;
  padding:0;
}
#root-app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
