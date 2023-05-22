
<script>
</script>


<script>
</script>

<template>
    <div class="big-cont-main">
        <div class="footer">
            <div>
                <ul class="list">
                    <li class="title">DC COMICS</li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
            <div>
                <ul class="list">
                    <li class="title">DC</li>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul> 
            </div> 
            <div>
                <ul class="list">
                    <li class="title">SITES</li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
            
                </ul>
                <ul class="list">
                    <li class="title">SHOP</li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
                <div class="cont-image-footer">
                    <img class="bg-image" src="../assets/img/dc-logo-bg.png" alt="">
                </div> 
            </div>
        
        
        </div>
    </div>
    
    <div class="bar-footer">
        <button class="button-footer">SIGN-UP NOW!</button>
        
        <div class="cont-icon">
            <h2 class="title-icon">FOLLOW US</h2>
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
            <img src="../assets/img/footer-periscope.png" alt="">
        </div>
        
    </div>
    
</template>

<style lang="scss" scoped>

.big-cont-main{
  background-image: url(../assets/img/footer-bg.jpg);
}


.footer{
    background-image: url(../assets/img/footer-bg.jpg);
    height: 400px;
    display: flex;
    gap: 1rem;
    
}

.list{
    margin-top: 2rem;
    color: gray;
    list-style: none;

    .title{
        color: white;
        font-size: 1.7rem;
    }
    
}


.bar-footer{
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: rgb(30, 30, 30);
    height: 90px;
}

.button-footer{
    background-color: rgb(27, 27, 27);
    color: white;
    margin-left: 8rem;
    height: 40px;
    width: 150px;
    border: 3px solid  rgb(4, 123, 235);
}

.cont-icon{
    height: 30px;
    display: flex;
    gap: .7rem;
}

.title-icon{
    color: rgb(4, 130, 249);
}


.bg-image{
    height: 446px;
     position: relative;
     top: -254px;
     right: -350px;
    

}
</style>
