<template>
<footer>
    <div class="footer-top-blue">
        <div class="container">
            <div class="footer-top-img">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="footer-top-img">
               <img src="../assets/img/buy-comics-merchandise.png" alt="">
               <span>DC MERCHANDISE</span>
            </div>
            <div class="footer-top-img">
               <img src="../assets/img/buy-comics-subscriptions.png" alt="">
               <span>SUBSCRIPTION</span>
            </div>
            <div class="footer-top-img">
               <img src="../assets/img/buy-comics-shop-locator.png" alt="">
               <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="footer-top-img">
               <img src="../assets/img/buy-dc-power-visa.svg" alt="">
               <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
    <div class="middle-footer">
        <div class="container">
            <div class="info-col first-info-col">
                <h3 class="white-text">DC COMICS</h3>
                <ul>
                    <li><a href="#">characters</a></li>
                    <li><a href="#">comics</a></li>
                    <li><a href="#">movies</a></li>
                    <li><a href="#">tv</a></li>
                    <li><a href="#">games</a></li>
                    <li><a href="#">videos</a></li>
                    <li><a href="#">news</a></li>
                </ul>
                <h3 class="white-text">SHOP</h3>
                <ul>
                    <li><a href="#">shop DC</a></li>
                    <li><a href="#">shop DC collectibles</a></li>
                </ul>
            </div>
            <div class="info-col">
               <h3 class="white-text">DC</h3>
               <ul>
                  <li><a href="#">terms of use</a></li>
                  <li><a href="#">privacy policy (New)</a></li>
                  <li><a href="#">ad choices</a></li>
                  <li><a href="#">advertising</a></li>
                  <li><a href="#">jobs</a></li>
                  <li><a href="#">subscriptions</a></li>
                  <li><a href="#">talent workshop</a></li>
                  <li><a href="#">cpsp certificates</a></li>
                  <li><a href="#">ratings</a></li>
                  <li><a href="#">shop help</a></li>
                  <li><a href="#">contact us</a></li>
               </ul>
            </div>
            <div class="info-col">
                <h3 class="white-text">SITES</h3>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD magazine</a></li>
                    <li><a href="#">DC kids</a></li>
                    <li><a href="#">DC universe</a></li>
                    <li><a href="#">DC power visa</a></li>
                </ul>
            </div>
        </div>
    </div>
    <div class="bottom-social-footer">
        <div class="container">
            <button>SIGN-UP NOW!</button>
            <div class="social-icons">
                <a href="">FOLLOW US</a>
                <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
            </div>
        </div>
    </div>
</footer>
</template>

<script>
export default {
    name: 'BaseFooter',
}
</script>

<style lang="scss" scoped>
.footer {
    &-top-blue {
        background-color: var(--secondary-color);
        display: flex;
    }
    &-top-img{
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 3.5rem 0;

        img{
            height: 2.5rem;
            width: 2.5rem;
        }
        span{
            margin-left: .625rem;
            justify-content: center;
            color: white;
            font-size: 10px;
        }
    }

    &-top-blue .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
    
}

.middle-footer {
    background-image: url(../assets/img/footer-bg.jpg);
    overflow: hidden;
    position: relative;
}

.middle-footer .container {
    display: flex;
    padding: 1.25rem 0;
}


.info-col {
    margin-right: 1.25rem;
    line-height: 0.9rem;
}

.first-info-col {
    line-height: 1rem;
}

.info-col ul {
    list-style: none;
}

.info-col li a {
    text-decoration: none;
    color: #959595;
    font-size: .65rem;
}

.info-col h3 {
    font-size: .9rem;
    padding: .6125rem 0;

}
.bottom-social-footer {
    background-color: #303030;
    padding: 1.40rem 0;
}

.bottom-social-footer .container {
    display: flex;
    justify-content: space-between;  
}

.bottom-social-footer button{
    padding: .6rem;
    background-color: transparent;
    border: 1px solid var(--primary-color);
    color: white;
    cursor: pointer;
    }

.social-icons {
    display: flex;
    column-gap: .9375rem;
    align-items: center;
}
 .social-icons a:first-child  {
    text-decoration: none;
    color: var(--primary-color);
    font-weight: bold;
    margin-right: .625rem;
}

</style>