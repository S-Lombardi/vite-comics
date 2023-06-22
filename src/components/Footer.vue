<script>

</script>


<template>
    <footer>
        <!-- TOP FOOTER -->
        <div id="top-footer">
            <div class="container">
                <div class="row">
                    <ul class="top-footer">
                        <li>
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                            <a href="#">Digital Comics</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                            <a href="#">Dc Merchandise</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                            <a href="#">Subcrtiption</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                            <a href="#">Comics shop Locator</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                            <a href="#">Dc Power Visa</a>
                        </li>
                            
                    </ul>
                </div>
            </div>
        </div>
        <!-- FINE TOP FOOTER -->
        <!-- CENTER FOOTER -->
        <div id="center-footer">
            <div class="container">
                <div class="row">
                    <ul>
                        <li><strong>DC COMICS</strong></li>
                        <li><a href="#">Chacarters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">Tv</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                            
                    </ul>
    
                    <ul>
                        <li><strong>DC</strong></li>
                        <li><a href="#">Terms of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Add Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Job</a></li>
                        <li><a href="#">Subcriptios</a></li>
                        <li><a href="#">Talent Workshop</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Rating</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contacts Us</a></li>      
                    </ul>
    
                    <ul>
                        <li><strong>Sites</strong></li>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">Mad Magazine</a></li>
                        <li><a href="#">Dc Kids</a></li>
                        <li><a href="#">Dc Universe</a></li>
                        <li><a href="#">Dc Power Visa</a></li>
                              
                    </ul>
                    <ul class="absolute">
                        <li><strong>Shop</strong></li>
                        <li><a href="#">Shop Dc</a></li>
                        <li><a href="#">Shop Dc Collectibles</a></li>
    
                    </ul>
                </div>
            </div>
            
            <!-- <img src="../assets/img/dc-logo-bg.png" alt="bg"> -->
            
        </div>
        <!-- FINE CENTER FOOTER -->
        <!-- BOTTOM FOOTER -->
        <div id="bottom-footer">
            <div class="container">
                <div class="row">
                    <!-- PULSANTE -->
                    <div class="col-left">
                        <button>
                            SIGN-UP NOW!
                        </button>
                    </div>
                    <!-- LINK -->
                    <div class="col-right">
                        <ul>
                            <li><strong>Follow us</strong></li>
                            <li>
                                <a href="#">
                                    <img src="../assets/img/footer-facebook.png" alt="face">
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    <img src="../assets/img/footer-twitter.png" alt="face">
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    <img src="../assets/img/footer-youtube.png" alt="face">
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    <img src="../assets/img/footer-pinterest.png" alt="face">
                                </a>
                            </li>
                            <li>
                                <a href="#">
                                    <img src="../assets/img/footer-periscope.png" alt="face">
                                </a>
                            </li>
                        
                        </ul>
                    
                    </div>
    
                </div>
            </div>
    
        </div>
        <!-- FINE BOTTOM FOOTER -->
    </footer>
</template>


<style lang="scss" scoped>
@use '../styles/partials/variables' as*;

//TOP FOOTER
#top-footer{
    background-color: $primary_color;
    padding: 40px 0px;
}
.top-footer{
    width: 100%;
    display: flex;
    justify-content: center;
    justify-content: space-evenly;

    li{
        display: flex;
        a{
            color: white;
            align-self:center;
            margin-left: 10px;
            font-family: $font_family;
        }
        img{
            height: 60px;
        }
  
    }
    
}
//FINE TOP FOOTER

// CENTER FOOTER

#center-footer{
    padding: 70px 0px;
    background-image: url(../assets/img/footer-bg.jpg);

    ul{
        margin-right: 20px;
        li{
            strong{
                color: white;
                font-size: 21px;
            }
            a{
                color: rgb(138, 138, 138);
                line-height: 25px;
                font-family: $font_family;
            }
       }      
    }  
}
// FINE CENTER FOOTER


//FOOTER BOTTOM
#bottom-footer{
    background-color: $gray_color;
    padding: 30px 0px;
    .row{
        justify-content: space-between;

        button{
            padding: 10px 20px ;
            border: 2px solid $primary_color;
            cursor: pointer;
            font-weight:800;
            color: white;
            background-color: rgba(255, 0, 0, 0);
            font-family: $font_family;
        }

        ul{
            height: 100%;
            display: flex;
            align-items: center;
            li{
                margin-left: 10px;

                strong{
                    color: $primary_color;
                    text-transform: uppercase;
                    font-family: $font_family;
                }
            }

        }
    }

    
}
//FINE FOOTER BOTTOM



</style>