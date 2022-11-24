<template>
   <div class="card">
    <img :src="dettagliProdotto.thumb" alt="">
    <h4>{{ dettagliProdotto.series }}</h4>
   </div>
</template>
  
  <script>
  
  export default {
    name: 'FumettoCard',
    props:{
        dettagliProdotto: Object
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  
  @import "../style/variabili.scss";

.card{
    width: calc(100%/6);
}
 
  </style>