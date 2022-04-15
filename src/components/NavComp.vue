<template>
  <div class="centro">
    <img src="/img/dc-logo.png" alt="">
    <ul>
      <li> 
        <a href="#">Characters</a>  
      </li>
      <li>
        <a href="#">Comics</a> 
      </li>
      <li>
        <a href="#">Movies</a>
      </li>
      <li>
        <a href="#">TV</a>
      </li>
      <li>
        <a href="#">Games</a>
      </li>
      <li>
        <a href="#">Collectibles</a>
      </li>
      <li>
        <a href="#">Videos</a>
      </li>
      <li>
        <a href="#">Fans</a>
      </li>
      <li>
        <a href="#">News</a>
      </li>
      <li>
        <a href="#">Shop</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'NavComp',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variabili.scss';

.centro{
  padding: 10px 0;
  display: flex;
  align-items: center;
  justify-content: space-around;

}

ul{
  list-style-type: none;
  display: flex;
} 

li{
  margin: 0 20px;
}

a{
  text-decoration: none;
  color: $color-grey;
  font-size: 1.2em; 
}

</style>
