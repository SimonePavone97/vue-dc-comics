<template>
    <div class="blu">
        <ul>
          <li>
            <img src="/img/buy-comics-digital-comics.png" alt="">
            <a href="#"> DIGITAL COMICS </a>
          </li>

          <li>
             <img src="/img/buy-comics-merchandise.png" alt="">
             <a href="#"> DIGITAL COMICS </a>
          </li>

          <li>
             <img src="/img/buy-comics-subscriptions.png" alt="">
             <a href="#"> DIGITAL COMICS </a>
          </li>

          <li>
             <img src="/img/buy-comics-shop-locator.png" alt="">
             <a href="#"> DIGITAL COMICS </a>
          </li>

          <li>
            <img src="/img/buy-comics-shop-locator.png" alt="">
            <a href="#"> DIGITAL COMICS </a>
          </li>

        </ul>
    </div>
</template>

<script>
export default {
  name: 'DigitalComp',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variabili.scss';

.blu{
  background: $color-blu;
  padding: 20px 0;
  display: flex;
  justify-content: center;
}


ul{
  list-style-type: none;
  display: flex;
} 

li{
  display: flex;
  align-items: center;
  img{
      height: 120px;
  }
}

a{
  margin: 0 20px;
  text-decoration: none;
  color: $light-white;  
}



</style>
