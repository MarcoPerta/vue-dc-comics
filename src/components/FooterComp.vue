<template>
    <div class="container-full">
        <div class="bg-image">
            <div class="footer-list">
                
            </div>
            <div class="image-dc">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="footer-icons">
            <div class="footer-center"></div>
        </div>
    </div>
</template>
  
<script>
  export default {
    name: 'FooterComp'
  }
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .bg-image{
    background-image: url(../assets/img/footer-bg.jpg);
    height: 100px;
    display: flex;
  }

  .footer-icons{
    background-color: #303030;
  }
</style>