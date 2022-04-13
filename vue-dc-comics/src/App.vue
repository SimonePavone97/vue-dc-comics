<template>
  <div id="app">
    <header>
      <NavComp/>
    </header>

    <main>
      <BarraNera/>
      <DigitalComp/>
    </main>


  </div>
</template>

<script> 
import NavComp from './components/NavComp.vue'
import BarraNera from './components/BarraNera.vue'
import DigitalComp from './components/DigitalComp.vue'




export default {
  name: 'App',
  components: {
    NavComp,
    BarraNera,
    DigitalComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>