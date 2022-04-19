<template>
  <div>
    <ul>
      <li v-for="(element, index) in menuLink" :key="index">
        <a :href="element.url"> {{element.link}} </a>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'NavComp',
    data() {
      return {
        menuLink: [{
            link: 'Characters',
            url: '#'
          },
          {
            link: 'Comics',
            url: '#'
          },
          {
            link: 'Movie',
            url: '#'
          },
          {
            link: 'Tv',
            url: '#'
          },
          {
            link: 'Games',
            url: '#'
          },
          {
            link: 'Collectibles',
            url: '#'
          },
          {
            link: 'Videos',
            url: '#'
          },
          {
            link: 'Fans',
            url: '#'
          },
          {
            link: 'News',
            url: '#'
          },
          {
            link: 'Shop',
            url: '#'
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

    li {
      margin: 0 20px;
    }

    a {
      text-decoration: none;
      color: black;
      text-transform: uppercase;
      font-weight: bold;
    }
  }
</style>