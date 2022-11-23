<template>
    <div class="footer-icons">
            <div class="footer-center">
                <button class="btn">SIGN-UP NOW!</button>
                <div class="right">
                    <h4>FOLLOW US</h4>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'FooterCompIcons'
}
</script>

<style scoped lang="scss">

@import "../style/variabili.scss";

  .footer-icons{
    background-color: #303030;
    .footer-center{
        width: $eigthypercent;
        margin: $auto ;
        display: $d-flex ;
        justify-content: $justify-content-between ;
        align-items: $center ;
        .btn{
            border-color: blue;
            padding: 8px;
            color: $color-white;
            background-color: #303030;
        }
        .right{
            display: $d-flex ;
            align-items: $center;
            .h4{
                padding: 5px;
                color:blue
            }
            img{
                padding: 5px;
            }
        }
    }
  }
</style>