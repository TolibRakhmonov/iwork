<template>
    <div class="services">
        <section>
            <div class="text-center hash">
                <img src="~assets/imgs/hash.png" alt="Image">
            </div>
            <div class="text-center title_div">
                <h3 class="page_title">
                    Полноценное рабочее место, которое включает в себя:
                </h3>
            </div>
            <div class="content1">
                <div class="txt_box1 text-center">
                    <h5 class="txt1">Ящики для хранения личных вещей</h5>
                </div>
                <div class="txt_box2 text-center">
                    <h5 class="txt2">Доступ к МФУ</h5>
                </div>
                <div class="txt_box3 text-center">
                    <h5 class="txt3">Высокоскоростной интернет</h5>
                </div>
                <div class="txt_box4 text-center">
                    <h5 class="txt4">Концелярские товары</h5>
                </div>
                 <div class="txt_box5 text-center">
                    <h5 class="txt5">Техническая поддержка</h5>
                </div>
            </div>
        </section>
        <section>
            <tarifs />
        </section>
        <section>
            <div class="content3">
                <div class="text-center hash">
                    <img src="~assets/imgs/hash.png" alt="Image">
                </div>
                <div class="text-center section_title">
                    <h4>
                       Наши услуги для вас 
                    </h4>
                </div>
                <div class="container">
                    <div class="row">
                        <div class="col-sm-4 service_col">
                            <div class="col1">
                                <div class="text-center">
                                    <img src="~assets/imgs/internet.png" alt="Image">
                                </div>
                                <div class="text-center serv_desc item">
                                    <h5 class="serv_txt">
                                    Быстрый, беспроводной
                                    интернет нового поколения без
                                    лимитов и ограничения трафика
                                    </h5>
                                </div>
                                <div class="text-center">
                                    <img src="~assets/imgs/meet.png" alt="Image">
                                </div>
                                <div class="text-center serv_desc item">
                                    <h5 class="serv_txt">
                                    Место для встречи с клиентами, руководителями
                                    и специалистами
                                    </h5>
                                </div>
                                <div class="text-center">
                                    <img src="~assets/imgs/study.png" alt="Image">
                                </div>
                                <div class="text-center serv_desc item">
                                    <h5 class="serv_txt">
                                    Ежедневное обучение
                                    происходит за счет знакомства с новыми людьми
                                    </h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-sm-4 service_col">
                            <img src="~assets/imgs/table.png" alt="Image">
                        </div>
                        <div class="col-sm-4 service_col">
                            <div class="col1">
                                <div class="text-center">
                                    <img src="~assets/imgs/ad.png" alt="Image">
                                </div>
                                <div class="text-center serv_desc item">
                                    <h5 class="serv_txt">
                                    Возможность продвигать и рекламировать
                                    свои услуги
                                    потенциальным заказчикам
                                    </h5>
                                </div>
                                <div class="text-center">
                                    <img src="~assets/imgs/technology.png" alt="Image">
                                </div>
                                <div class="text-center serv_desc item">
                                    <h5 class="serv_txt">
                                    Использование техники и технологий
                                    (специализированный софт, оборудование, 3Д-принтеры)
                                    </h5>
                                </div>
                                <div class="text-center">
                                    <img src="~assets/imgs/hakaton.png" alt="Image">
                                </div>
                                <div class="text-center serv_desc item">
                                    <h5 class="serv_txt">
                                    Возможность проведения различных презентаций,
                                    мастер-классов и  хакатонов
                                    </h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .services{
        padding-top: 80px;
    }
    .hash{
        padding-bottom: 20px;
    }
    .title_div{
        padding-bottom: 30px;
    }
    .page_title{
        height: 30px;
        color: #272727;
        font-family: "Open Sans";
        font-size: 30px;
        font-weight: 400;
        line-height: 38px; 
    }
    .content1{
        background: url('~assets/imgs/bg_image.png');
        width: 100%;
        height: 610px;
    }
    .txt_box1{
        width: 378px;
        height: 51px;
        box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
        background-color: #eab612;
        position: absolute;
        top: 55%;
        left: 28%;
        transform: translate(-55%, -28%);
        padding-top: 5px;  
    }
    .txt1{
        height: 18px;
        text-shadow: 0 1px 0 rgba(0, 0, 0, 0.35);
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 18px;
        font-weight: 700;
        line-height: 38px;
    }
    .txt_box2{
        width: 191px;
        height: 51px;
        box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
        background-color: #eab612;
        position: absolute;
        top: 70%;
        left: 50%;
        transform: translate(-70%, -50%);
        padding-top: 5px;
    }
    .txt2{
        height: 17px;
        text-shadow: 0 1px 0 rgba(0, 0, 0, 0.35);
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 18px;
        font-weight: 700;
        line-height: 38px;
    }
    .txt_box3{
        width: 340px;
        height: 45px;
        box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
        background-color: #2ebd7f;
        padding-top: 2px;
        position: absolute;
        top: 40%;
        left: 55%;
        transform: translate(-40%, -55%);
    }
    .txt3{
        height: 18px;
        text-shadow: 0 1px 0 rgba(0, 0, 0, 0.35);
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 18px;
        font-weight: 700;
        line-height: 38px;
    }
    .txt_box4{
        width: 268px;
        height: 51px;
        box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
        background-color: #eab612;
        padding-top: 5px;
        position: absolute;
        top: 30%;
        left: 65%;
        transform: translate(-30%,-65%);
    }
    .txt4{
        height: 17px;
        text-shadow: 0 1px 0 rgba(0, 0, 0, 0.35);
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 18px;
        font-weight: 700;
        line-height: 38px;
    }
    .txt_box5{
        width: 300px;
        height: 45px;
        box-shadow: 0 5px 0 rgba(0, 0, 0, 0.2);
        background-color: #eab612;
        padding-top: 2px;
        position: absolute;
        top: 45%;
        left: 90%;
        transform: translate(-45%, -90%);
    }
    .txt5{
        height: 17px;
        text-shadow: 0 1px 0 rgba(0, 0, 0, 0.35);
        color: #ffffff;
        font-family: "Open Sans";
        font-size: 18px;
        font-weight: 700;
        line-height: 38px;
    }
    .content3{
        width: 100%;
        height: 760px;
        background-color: rgba(255, 255, 255, 0.76);
    }
    .hash{
        padding-top: 20px;
    }
    .section_title{
        height: 28px;
        color: #272727;
        font-family: "Open Sans";
        font-size: 30px;
        font-weight: 400;
        line-height: 38px;
    }
    .service_col{
        height: 508px;  
    }
    .col1{
        margin-top: 20px;
    }
    .serv_desc{
        height: 57px;
        color: #272727;
        font-family: "Open Sans";
        font-size: 16px;
        font-weight: 400;
        line-height: 20px;
        padding-top: 5px;
    }
    .serv_text{
        width: 267px;
    }
    .item{
        margin-bottom: 50px;
    }
    





    
</style>
