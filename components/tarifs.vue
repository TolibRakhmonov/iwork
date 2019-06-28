<template>
    <div class="tarifs">
        <div class="text-center hash">
            <img src="~assets/imgs/hash.png" alt="Hash">
        </div>
        <div class="text-center title_div">
            <h4 class="section_title">
                Тарифные планы
            </h4>
        </div>
        <div class="container"> 
            <div class="row">
                <div class="col-sm-4">
                    <div class="tarif_img1 text-center">
                            <h4 class="tarif_name">
                                Гибкий график
                            </h4>  
                    </div>
                    <div class="price_div text-center">
                        <p class="price">
                           120 000 сум / месяц 
                        </p>
                    </div>
                    <div class="tarif_body">
                        <div class="tarif_desc text-center">
                            <p>
                               1 день / мес включено<br>
                              1 ч / мес Конференц-залы<br>
                              Высокоскоростной интернет<br>
                            Доступ к профессиональной сети<br>
                              Кухня, бесплатный кофе<br>
                                         —<br>
                                         —<br>
                                         — 
                            </p>
                            
                        </div>
                        <div class="text-center buy_div">
                            <nuxt-link to="#">
                            <div class="buy">
                                <h5 class="buy_txt">Купить</h5>
                            </div>
                            </nuxt-link>
                        </div>

                    </div>
                </div>
                <div class="col-sm-4">
                     <div class="tarif_img2 text-center">
                            <h4 class="tarif_name">
                                Неполная занятость
                            </h4>  
                    </div>
                    <div class="price_div text-center">
                        <p class="price">
                           500 000 сум / месяц
                        </p>
                    </div>
                    <div class="tarif_body">
                        <div class="tarif_desc text-center">
                            <p>
                               3 день / мес включено<br>
                              2 ч / мес конференц-залы<br>
                              Высокоскоростной интернет<br>
                            Доступ к профессиональной сети<br>
                              Кухня, бесплатный кофе<br>
                                Семинары / Лекции<br>
                                Менеджеры сообщества<br>
                                         — 
                            </p>
                            
                        </div>
                        <div class="text-center buy_div">
                            <nuxt-link to="#">
                            <div class="buy">
                                <h5 class="buy_txt">Купить</h5>
                            </div>
                            </nuxt-link>
                        </div>

                    </div>

                </div>
                <div class="col-sm-4">
                     <div class="tarif_img3 text-center">
                            <h4 class="tarif_name">
                                На постоянной основе
                            </h4>  
                    </div>
                    <div class="price_div text-center">
                        <p class="price">
                           1 000 000 сум / месяц
                        </p>
                    </div>
                    <div class="tarif_body">
                        <div class="tarif_desc text-center">
                            <p>
                            Неограниченное количество<br>
                              рабочих часов<br>
                              конференц-залов<br>
                              Неограниченное количество <br>
                              Высокоскоростной интернет<br>
                            Доступ к профессиональной сети<br>
                              Кухня, бесплатный кофе<br>
                               Семинары / Лекции<br>
                                Прием гостей           
                            </p>
                            
                        </div>
                        <div class="text-center buy_div">
                            <nuxt-link to="#">
                            <div class="buy">
                                <h5 class="buy_txt">Купить</h5>
                            </div>
                            </nuxt-link>
                        </div>

                    </div>

                </div>
            </div>
       </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .tarifs{
        width: 100%;
        height: 713px;
        background-color: #f9f9f9;
    }
    .hash{
        padding-top: 30px;
        padding-bottom: 30px;
    }
    .title_div{
        padding-bottom: 30px;
    }
    .section_title{
        height: 30px;
        color: #272727;
        font-family: "Open Sans";
        font-size: 30px;
        font-weight: 400;
        line-height: 38px;
    }
    .tarif_img1{
        background: url('~assets/imgs/flexible.png');
        width: 308px;
        height: 106px;
        padding-top: 50px;
    }
    .tarif_img2{
        background: url('~assets/imgs/incomplete.png');
        width: 308px;
        height: 106px;
        padding-top: 50px;
    }
    .tarif_img3{
        background: url('~assets/imgs/fixed.png');
        width: 308px;
        height: 106px;
        padding-top: 50px;
    }
    .tarif_name{
        height: 20px;
        color: #eeba11;
        font-family: "Open Sans";
        font-size: 20px;
        font-weight: 700;
        text-transform: uppercase;
    }
    .price_div{
        width: 308px;
        height: 48px;
        background-color: #2ebd7f; 
        padding-top: 8px;
    }
    .price{
        height: 20px;
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 20px;
        font-weight: 700;  
    }
    .tarif_body{
        width: 308px;
        height: 380px;
        box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
        border-radius: 10px;
        border: 1px solid #e4e4e4;
        background-color: #ffffff;
    }
    .tarif_desc{
        height: 253px;
        color: #272727;
        font-family: "Open Sans";
        font-size: 16px;
        font-weight: 400;
        line-height: 35px;
    }
    .buy_div{
        margin-top: 60px;
    }
    .buy{
        width: 149px;
        height: 37px;
        box-shadow: 0 3px 0 #272727;
        border-radius: 19px;
        background-color: #2ebd7f;
        margin: auto;  
        padding-top: 11px;    
    }
    .buy_txt{
        height: 12px;
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 14px;
        font-weight: 700;
        line-height: 17.99px;
        text-transform: uppercase;
    }
</style>
