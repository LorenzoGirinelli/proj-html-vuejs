<template>
    <header>
        <div class="head container">
             <!-- Logo -->
            <div class="logo">
                <img src="../assets/img/dark-logo.png" alt="logo">
            </div>
             <!-- Header Nav -->
            <div>
                <div class="nav">
                    <div class="nav-element">
                          Home <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="nav-element">
                        Pages <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="nav-element">
                        Courses <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="nav-element">
                        Features <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="nav-element">
                        Bolg <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="nav-element">
                        Shop <i class="fas fa-chevron-down"></i>
                    </div>
                </div>
            </div>
            <div class="social-media">
                <div class="social">
                    <i class="fab fa-twitter"></i>
                </div>
                <div class="social">
                    <i class="fab fa-facebook-f"></i>
                </div>
                <div class="social">
                    <i class="fab fa-instagram"></i>
                </div>
                <div class="social">
                    <i class="fab fa-linkedin"></i>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped lang="scss">
@import '../style/general.scss';
// header{
//         position: absolute;
// }
.head{
    font-family: 'Playfair Display', serif;
    height: 105px;
    line-height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    .logo{
        img{
            width: 170px;
        }
    }
    .nav{
        display: flex;
        .nav-element{
            padding: 17px;
            color: #767291;
            i{
                font-size: 8px;
                vertical-align: middle;
            }
        }
    }
    .social-media{
        display: flex;
        .social{
            padding: 5px;
            font-size: 18px;
        }
    }
}
</style>