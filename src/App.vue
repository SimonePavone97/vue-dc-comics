<template>
  <div id="app">
    <header class="container">
      <LogoComp />
      <NavComp />
    </header>

    <main>
      <div class="content">
        <div class="container">
          <h1>Il contenuto va qui</h1>
        </div>
      </div>

      <div class="icons">
        <DigitalComp />
      </div>


    </main>

    <HelloFoot />
    <FootSocial />

  </div>
</template>

<script>
  import LogoComp from './components/LogoComp.vue'
  import NavComp from './components/NavComp.vue'
  import DigitalComp from './components/DigitalComp.vue'
  import HelloFoot from './components/HelloFoot.vue'
  import FootSocial from './components/FootSocial.vue'


  export default {
    name: 'App',
    components: {
      LogoComp,
      NavComp,
      DigitalComp,
      HelloFoot,
      FootSocial
    }
  }
</script>

<style lang="scss">
  @import './style/global.scss';
  @import './style/variabili.scss';
  @import './style/reset.scss';


  header {
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .content {
    background-color: black;
    padding: 20px 0;
    color: white;
  }

  .icons {
    background-color: $color-blu;
    padding: 20px 0;
  }

  footer {
    background: url('./assets/img/footer-bg.jpg');
    background-size: cover;
  }
</style>