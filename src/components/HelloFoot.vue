<template>
<footer>
    <div class="col">
          <ul>
              <li>
                  <h2>TERM OF US</h2>
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
                  <a href="#">Videos</a>
              </li>
              <li>
                  <a href="#">News</a>
              </li>
              <li>
                  <h2>SHOP</h2>
                  <a href="#">Shop DC</a>
              </li>
              <li>
                  <a href="#">Shop DC Collectibles</a>
              </li>
          </ul>

          <ul>
            <li>
                <h2>DC</h2>
            </li>
            <li>
                <a href="#">Term of use</a>
            </li>
            <li>
                <a href="#">Privacy policy (New)</a>
            </li>
            <li>
                <a href="#">Ad Choises</a>
            </li>
            <li>
                <a href="#">Advertising</a>
            </li>
            <li>
                <a href="#">Jobs</a>
            </li>
             <li>
                <a href="#">Subscriptions</a>
            </li>
             <li>
                <a href="#">Talent Workshop</a>
            </li>
             <li>
                <a href="#">CPSC</a>
            </li>
             <li>
                <a href="#">Ratings</a>
            </li>
             <li>
                <a href="#">Shop help</a>
            </li>
             <li>
                <a href="#">Contact US</a>
            </li>
          </ul>

          <ul>
            <li>
                <h2>SITES</h2>
            </li>
            <li>
                <a href="#">Dc</a>
            </li>
            <li>
                <a href="#">MAD magazines</a>
            </li>
            <li>
                <a href="#">DC kids</a>
            </li>
            <li>
                <a href="#">Dc universe</a>
            </li>
            <li>
                <a href="#">Jobs</a>
            </li>
          </ul>
    </div>
    
    <div class="col">
        <img class="dimension" src="/img/dc-logo-bg.png" alt="">
    </div>
</footer>
  
</template>

<script>
export default {
  name: 'HelloFoot',
  
} 
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variabili.scss';

footer{
    display: flex;
    margin: 0 auto;
}


.col{
    width: calc(100%/2);
    display: flex;
    justify-content: center;
    
}




ul{
  list-style-type: none;
  display: flex;
  flex-direction: column;
}

li{
    margin: 0 20px;
}
    
a{
    text-decoration: none;
    color: $color-grey;
    font-size: 0.8em; 
}

h2{
    color: $light-white;
   
}

</style>
