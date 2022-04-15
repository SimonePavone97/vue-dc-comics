<template>
  <div id="app">
    <header>
      <NavComp/>
    </header>

    <main>
      <BarraNera/>
      <DigitalComp/>
    </main>

    <HelloFoot/>
    

  </div>
</template>

<script> 
import NavComp from './components/NavComp.vue'
import BarraNera from './components/BarraNera.vue'
import DigitalComp from './components/DigitalComp.vue'
import HelloFoot from './components/HelloFoot.vue'





export default {
  name: 'App',
  components: {
    NavComp,
    BarraNera,
    DigitalComp,
    HelloFoot
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

footer{
  background: url('./assets/img/footer-bg.jpg');
  background-size: cover;
}

</style>