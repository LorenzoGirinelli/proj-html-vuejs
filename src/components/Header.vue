<template>
    <header>
        <div class="head container">
             <!-- Logo -->
            <div class="logo">
                <img src="../assets/img/dark-logo.png" alt="logo">
            </div>
            <div class="header-menu">
                    <ul>
                        <li 
                            v-for="(link, index) in links" 
                            :key="index"
                            :class="{ active: link.active }"
                        >
                            <a :href="link.href">{{ link.text }}</a>
                        </li>
                    </ul>
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

<script>
export default {
    name: "Header",
    data: function() {
        return {
            links: [
                {
                    href: '#',
                    text: 'Home',
                    active: false,
                },
                {
                    href: '#',
                    text: 'Pages',
                    active: true,
                },
                {
                    href: '#',
                    text: 'Courses',
                    active: false,
                },
                {
                    href: '#',
                    text: 'Features',
                    active: false,
                },
                {
                    href: '#',
                    text: 'Blog',
                    active: false,
                },
                {
                    href: '#',
                    text: 'Shop',
                    active: false,
                },
            ],
        }
    },
}
</script>

<style scoped lang="scss">
@import '../style/general.scss';
// header{
//         position: absolute;
// }
.head{
    font-family: 'Roboto', sans-serif;
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
    .header-menu {
                li {
                    display: inline-block;
                    line-height: 110px;
                    margin: 0 12px;
                    font-size: 15px;
                    color: #767291;
                }
                a {
                    text-decoration: none;
                    font-weight: bold;
                    color: #767291;
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