<template>
  <div class="container-full">

    <div class="container-cards">
        <div class="cards"> <h2>Content Goes Here</h2></div>
    </div>

    <MainShopBlue/>
    
  </div>
</template>

<script>
import MainShopBlue from './MainShopBlue.vue'

export default {
  name: 'MainComp',
  components: {
    MainShopBlue
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../style/variabili.scss";
.container-cards{
    background-color: black;
    .cards{
        padding: 20px;
        width:$eigthypercent;
        margin: $auto;
        h2{
            color: $color-white;
        }
    }
}

</style>