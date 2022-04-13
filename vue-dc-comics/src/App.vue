<template>
  <div id="app">
    <header>
      <NavComp/>
    </header>

    <main>
      <BarraNera/>
    </main>


  </div>
</template>

<script> 
import NavComp from './components/NavComp.vue'
import BarraNera from './components/BarraNera.vue'



export default {
  name: 'App',
  components: {
    NavComp,
    BarraNera
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