<script>
</script>

<template>
   <div class="main">
        <h2 class="text"> Content goes here</h2>
    </div>
    <div class="bar-main">
        <div class="cont-img">
            <img class="img-main" src="../assets/img/buy-comics-digital-comics.png" alt="">
            <h5>DIGITAL COMICS</h5>
        </div>
        <div class="cont-img">
            <img class="img-main" src="../assets/img/buy-comics-merchandise.png" alt="">
            <h5>DC MERCHANDISE</h5>
        </div>
        <div class="cont-img">
            <img class="img-main" src="../assets/img/buy-comics-subscriptions.png" alt="">
            <h5>SUBSCRIPTION</h5>
        </div>
        <div class="cont-img">
            <img class="img-main" src="../assets/img/buy-comics-shop-locator.png" alt="">
            <h5>COMIC SHOP LOCATOR</h5>
        </div>
        <div class="cont-img">
            <img class="img-main" src="../assets/img/buy-dc-power-visa.svg" alt="">
            <h5>DC POWER VISA</h5>
        </div>
    </div>
   
    
    
 
</template>

<style lang="scss" scoped>
@use './../assets/style/partials/_variables' as *;

.main{
    background-color: black;
        height: 150px;
}

.bar-main{
    display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: rgb(2, 130, 249);
        height: 200px;
        color: white;
}

.text{
    text-align: center;
        color: white;
}

.img-main{
    height: 50px;
}
.cont-img{
    display: flex;
        align-items: center;
        gap: 1.5rem;
}

</style>