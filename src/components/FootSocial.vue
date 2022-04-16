<template>
    <div class="foot-bar">
        <div>
            <button><strong>SIGN-UP NOW!</strong></button>
        </div>
        <div class="d-flex">
            <span class="colore"> <strong></strong> FOLLOW US</span>
            <img  class="dimensione" src="/img/footer-facebook.png" alt="">
            <img  class="dimensione" src="/img/footer-twitter.png" alt="">
            <img class="dimensione" src="/img/footer-youtube.png" alt="">
            <img class="dimensione" src="/img/footer-pinterest.png" alt="">
            <img  class="dimensione" src="/img/footer-periscope.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
  name: 'FootSocial',
  
} 
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variabili.scss';

.foot-bar{
    background: #303030;
    display: flex;
    align-items: center;
    justify-content: space-around;
    height: 80px;
}

.d-flex{
    display: flex;
    align-items: center;

}

button{
    background-color: transparent;
    border: 4px solid blue;
    padding: 14px;
    color: white;
}

.colore{
    color: blue;
}


.dimensione{
    margin: 0 5px;
}
</style>
