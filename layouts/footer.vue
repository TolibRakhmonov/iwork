<template>
<div>
    <footer>
        <div class="footer">
            <div class="text-center footer_logo">
                <img src="~assets/imgs/footer_logo.png" alt="Footer Logo">
            </div>
            <div class="text-center footer_icon">
                <div class="icon">
                    <nuxt-link to="#"><img src="~assets/imgs/f_icon.png" alt="Facebook"></nuxt-link>
                </div>
                <div class="icon">
                    <nuxt-link to="#"><img src="~assets/imgs/i_icon.png" alt="Instagram"></nuxt-link>
                </div>
                 <div class="icon">
                    <nuxt-link to="#"><img src="~assets/imgs/t_icon.png" alt="Telegram"></nuxt-link>
                </div>
            </div>
            <div class="text-center">
                <p class="footer_txt">
                    ©2016 iWork.uz. Все права защищены<br>
                    Разработка сайта:
                    <nuxt-link to="www.osg.uz" class="osg">Online Service Group</nuxt-link>
                </p>
            </div>
        </div>
    </footer>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .footer{
        width: 100%;
        background: url('~assets/imgs/footer_bg.png');
        padding-bottom: 30px;
    }
    .footer_logo{
        padding-top: 30px;
    }
    .icon{
        height: 29px;
        width: 29px;
        background-color: rgb(234,182,18);
        border-radius: 50%;
        display: inline-block;
        text-align: center;
        margin-left: 10px;
    }
    .footer_icon{
        padding-top: 20px;
        padding-bottom: 20px;
    }
    .footer_txt{
        height: 34px;
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 14px;
        font-weight: 400;
        line-height: 20px; 
    }
    .osg{
        color: #eab612;
        text-decoration: none;
    }
</style>
