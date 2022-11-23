<template>
    <div class="container-full">
        <div class="bg-image">
            <div class="footer-list">
                <div class="list-left">
                    <div>
                        <h3>DC COMICS</h3>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3>SHOP</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collections</a></li>
                        </ul>
                    </div>
                </div>
                <div class="list-center">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy Policy(New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Wotkshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="list-left">
                    <h3>SITES</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
            <div class="image-dc">
                <!-- <img src="../assets/img/dc-logo-bg.png" alt=""> -->
            </div>
        </div>
        
        <FooterCompIcons/>
    </div>
</template>
  
<script>
import FooterCompIcons from './FooterCompIcons.vue'

  export default {
    name: 'FooterComp',
    components: {
     FooterCompIcons
  }
  }
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../style/variabili.scss";
  .bg-image{
    background-image: url(../assets/img/footer-bg.jpg);
    display: $d-flex ;
    justify-content: $justify-content-between ;
    .footer-list{
        width: $eigthypercent;
        margin: $auto;
        display: $d-flex ;
        h3{
            color: $color-white;
            text-align: $center;
        }
         ul{
            text-align: $left;
            li{
                list-style-type: $none;
                padding: 3px;
                 a{
                    text-decoration: $none;
                    color: $color-grey;
                 }
            }
         }
    }
  }

</style>