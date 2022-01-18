<template>
    <main>
        <div class="jumbotron">
            <div class="jumbo container">
                <div class="jumbo-text">
                    <h3>I'M WINGMAN</h3>
                    <h2>Peace on Earth A Wondewrful Wish But No Way</h2>
                    <p>Success isn't overnight. It's when everyday you get a little better then the day before. It all adds up.</p>
                    <button class="green_btn">
                        Get Started For Free <i class="fas fa-long-arrow-alt-right"></i>
                    </button>
                </div>
                <img src="../assets/img/home-movation-hero-image.png" alt="">
            </div>
        </div>
        <div class="stats container">
            <div class="single-stats">
                <img src="../assets/img/background-pattern-grid-line-06.png" alt="">
                <div class="stats-text">
                    <h2>1.926</h2>
                    <span>FINISHED SESSION</span>
                </div>
            </div>
            <div class="single-stats">
                <img src="../assets/img/background-pattern-grid-line-06.png" alt="">
                <div class="stats-text">
                    <h2>100%</h2>
                    <span>SATISFACITON RATE</span>
                </div>
            </div>
            <div class="single-stats">
                <img src="../assets/img/background-pattern-grid-line-06.png" alt="">
                <div class="stats-text">
                    <h2>3092+</h2>
                    <span>ENROLLED LEARNERS</span>
                </div>
            </div>
            <div class="single-stats">
                <img src="../assets/img/background-pattern-grid-line-06.png" alt="">
                <div class="stats-text">
                    <h2>200</h2>
                    <span>ONLINE INSTRUCTORS</span>
                </div>
            </div>
        </div>
    </main>
</template>

<style scoped lang="scss">
@import '../style/general.scss';
.jumbo{
    background-image: url("../assets/img/background-pattern-wavify.png");
    font-family: 'Playfair Display', serif;
    display: flex;
    align-items: center;
    padding-top: 100px;
    .jumbo-text{
        padding-right: 300px;
        h3{
            font-weight: lighter;
            font-size: 17px;
        }
        h2{
            font-size: 55px;
            line-height: 75px;
            font-weight: lighter;
        }
        p{
            line-height: 30px;
            color: #333333;
            padding-top: 20px;
        }
    }
}
.stats{
    font-family: 'Aleo', serif;
    margin-top: 100px;
    display: flex;
    justify-content: space-between;
    .single-stats{
        .stats-text{
            position: absolute;
            top: 1000px;
            padding-left: 80px;
            text-align: center;
            font-size: 16px;
            font-weight: bold;
            line-height: 45px;
        }
        h2{
            font-size: 35px;
            color: #20ad96;
            
        }
    }
}
</style>