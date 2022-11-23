<template>
    <div class="container-full">
        <div class="container">
            <div>
            <img src="../assets/img/dc-logo.png" alt="logo-dc">
        </div>
        <div>
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
        </div>
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
.container-full{
    background-color: white;
    .container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    margin: auto;
    padding: 15px;
    ul{
    display: flex;
    justify-content: space-between;
    li{
        list-style-type: none;
        padding: 5px;
        a{
            text-decoration: none;
            color: black;
        }
    }
    }
}
}

</style>