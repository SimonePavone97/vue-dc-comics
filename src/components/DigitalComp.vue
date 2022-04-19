<template>
  <div>
    <ul class="container">
      <li v-for="(element, index) in menuDigital" :key="index">
        <img :src="element.image" alt="">
        <a :href="element.url"> {{element.name}} </a>
      </li>

    </ul>
  </div>
</template>

<script>
  export default {
    name: 'DigitalComp',
    data() {
      return {
        menuDigital: [{
            name: 'Digital Comics',
            url: '#',
            image: 'img/buy-comics-digital-comics.png'
          },
          {
            name: 'Dc Merchandise',
            url: '#',
            image: 'img/buy-comics-merchandise.png'
          },
          {
            name: 'Subscription',
            url: '#',
            image: 'img/buy-comics-subscriptions.png'
          },
          {
            name: 'Comic Shop Locator',
            url: '#',
            image: 'img/buy-comics-shop-locator.png'
          },
          {
            name: 'Dc Power Visa',
            url: '#',
            image: 'img/buy-dc-power-visa.svg'
          }
        ]
      }
    }

  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import '../style/variabili.scss';


  ul {
    list-style-type: none;
    display: flex;
    justify-content: space-between;
  }

  li {
    display: flex;
    align-items: center;

    img {
      height: 70px;
    }
  }

  a {
    margin: 0 20px;
    text-decoration: none;
    color: $light-white;
    text-transform: uppercase;
    font-weight: bold;
  }
</style>