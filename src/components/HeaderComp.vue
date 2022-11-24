<template>
    <div class="container-full">
        <div class="container">
            <div>
            <img src="../assets/img/dc-logo.png" alt="logo-dc">
        </div>
        <nav>
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </nav>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HeaderComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../style/variabili.scss";
.container-full{
    background-color: $color-white ;
    .container{
    display: $d-flex;
    justify-content: $justify-content-between;
    align-items: $center ;
    width: $eigthypercent;
    margin: $auto;
    padding: 15px;
    ul{
    display: $d-flex;
    // justify-content:$justify-content-between;
    li{
        list-style-type: $none;
        padding: 30px 10px;
        a{
            text-decoration: $none;
            color: black;
        }
    }
    li:hover {
      border-bottom: 3px solid #0C7CEC;
    }   
    }
}
}

</style>