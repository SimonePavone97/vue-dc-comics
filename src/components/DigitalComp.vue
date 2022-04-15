<template>
    <div class="blu">
        <ul>
          <li>
            <img src="/img/buy-comics-digital-comics.png" alt="">
            <a href="#"> DIGITAL COMICS </a>
          </li>

          <li>
             <img src="/img/buy-comics-merchandise.png" alt="">
             <a href="#"> DC MERCHANDISE </a>
          </li>

          <li>
             <img src="/img/buy-comics-subscriptions.png" alt="">
             <a href="#"> SUBSCRIPTION </a>
          </li>

          <li>
             <img src="/img/buy-comics-shop-locator.png" alt="">
             <a href="#"> COMIC SHOP LOCATOR </a>
          </li>

          <li>
            <img src="/img/buy-dc-power-visa.svg" alt="">
            <a href="#"> DC POWER VISA </a>
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
      height: 70px;
  }
}

a{
  margin: 0 20px;
  text-decoration: none;
  color: $light-white;  
}



</style>
