<template>
  <div class="container-full">
    <div class="container-cards">
        <div class="cards"> <h2>Content Goes Here</h2></div>
    </div>
    <div class="container-icons-blue">
        <div class="icons-blue">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="dc-comics">
                <h4>DIGITAL COMICS</h4>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="dc-merchandising">
                <h4>DC MERCHANDISE</h4>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="sub">
                <h4>SUBSCRIPTION</h4>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="location-shops">
                <h4>COMIC SHOP LOCATION</h4>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="dc-power-visa">
                <h4>DC POWER VISA</h4>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-cards{
    background-color: black;
    .cards{
        padding: 20px;
        width: 80%;
        margin: auto;
        h2{
            color: white;
        }
    }
}

.container-icons-blue{
    background-color: #0C7CEC;
    .icons-blue{
        width: 80%;
        margin: auto;
        display: flex;
        padding: 15px;
        div{
            display: flex;
            padding: 10px;
            img{
                width: 80px;
                height: 80px;
            }
            h4{
                font-size: 12px;
                color: white;
                align-self: center;
                padding-left: 5px;
            }
        }
    }
}

</style>