<template>
<div class="header_top">
    <!-- <nav class="navbar navbar-expand-sm"> -->
        <!-- Brand/logo -->
        <a class="navbar-brand" href="#">
            <img src="~assets/imgs/logo.png" alt="logo">
        </a>
  
        <!-- Links -->
        <div class="desktop-menu">
            <h5> 
                <nuxt-link class="nav-link" to="/services">Услуги и цены</nuxt-link>
            </h5>
            <h5> 
                <nuxt-link class="nav-link" to="/discount">Акции и скидки</nuxt-link>
            </h5>
            <h5>
                <nuxt-link class="nav-link" to="#">Резиденты</nuxt-link>
            </h5>
            <h5> 
                <nuxt-link class="nav-link" to="#">Календаръ</nuxt-link>
            </h5>
            <h5>
                <nuxt-link class="nav-link" to="#">Галарея</nuxt-link>
            </h5>
            <h5>
                <nuxt-link class="nav-link" to="#">Новости</nuxt-link>
            </h5>
            <h5>
                <nuxt-link class="nav-link" to="#">Бронь</nuxt-link>
            </h5>
            <h5>
                <nuxt-link class="nav-link" to="#">Контакты</nuxt-link>
            </h5>  
        </div>
        <!-- Icons and Login -->
        <div class="icon_login">
            <div class="icon">
                <nuxt-link to="#"><img src="~assets/imgs/f_icon.png" alt="Facebook"></nuxt-link>
            </div>
            <div class="icon">
                <nuxt-link to="#"><img src="~assets/imgs/i_icon.png" alt="Instagram"></nuxt-link>
            </div>
            <div class="icon">
                <nuxt-link to="#"><img src="~assets/imgs/t_icon.png" alt="Telegram"></nuxt-link>
            </div>
            <div class="login">
                <nuxt-link class="nav-link" to="#">Войти</nuxt-link>
            </div>
        </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.header_top{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding: 0 50px;
    margin-top: 20px;
    background: #fff;
   
    margin-top: 0px;
    position: relative;
     position: fixed;
     z-index: 500;
}

.desktop-menu {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-between;
}

.desktop-menu  h5 {
    margin-bottom: 0;
}
h5 a{
    color: #000;
    font-size: 15px;
}
.icon_login{
    display: flex;
    align-items: center;
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
.login{
    display: inline-block;
    border-radius: 18.5px;
    border: 2px solid #2ebd7f;
    width: 118px;
    height: 37px; 
    margin-left: 15px;
    
    
}
.login a{
    color: #2ebd7f;
    font-size: 15px;
    position: relative;
    left: 20px;
    bottom: 3px;
    
}

</style>
