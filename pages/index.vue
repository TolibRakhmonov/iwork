<template>
 <div>
 <section>
   <div class="banner">
     <div class="banner_txt">
       <div class="logo">
         <img src="~assets/imgs/logotip.png" alt="Logo">
       </div>
       <div class="txt">
         <p>
           Общее пространство для работы и развития бизнеса
            Для бизнесменов, фрилансеров и стартап – проектов.
            Аренда рабочих мест, офисов, переговорных комнат, конференц - залов.
         </p>
       </div>
       <div class="book_rect">
         <nuxt-link class="book" to="#">Забронировать</nuxt-link>
       </div>
     </div>
   </div>
 </section>
 <section class="section2">
   <!-- Slider -->
   <div class="slider">
      <!-- swiper -->
      <swiper :options="swiperOption">
        <swiper-slide><img src="~assets/imgs/slide1.jpg" alt="Slide Image"></swiper-slide>
        <swiper-slide><img src="~assets/imgs/slide2.jpg" alt="Slide Image"></swiper-slide>
        <swiper-slide><img src="~assets/imgs/slide3.jpg" alt="Slide Image"></swiper-slide>
        <div class="swiper-pagination" slot="pagination"></div>
        <div class="swiper-button-prev" slot="button-prev"></div>
        <div class="swiper-button-next" slot="button-next"></div>
      </swiper>
   </div>
   <!-- Right content -->
   <div class="right_content">
     <div class="logo1">
       <img src="~assets/imgs/logo1.png" alt="Logo">
     </div>
     <div class="title text-center">
       <h4 class="logo_title">
         Немного о нас и о нашей цели
        </h4>
        <div class="logo_div">
        <p class="logo_text">
          Независимо от того, Вы работаете для себя или же удаленно, это здорово, это независимость. Наша цель состоит в том, чтобы создать среду, которая позволяет Вам сосредоточиться на том, что действительно важно, качественно сделать свою работу и познакомиться с интересными людьми.
          Все это в одном месте!
        </p>
        </div>
        <div class="resident">
            <nuxt-link to="#">
              <h3 class="resident_txt align-middle">стать резидентом</h3>
            </nuxt-link>
        </div>
     </div>
   </div>
 </section>
 <section>
   <div class="content3">
     <div class="text-center">
       <img src="~assets/imgs/hash.png" alt="Line">
     </div>
     <div class="container section_title">
       <h4 class="text-center">
         Основные преимущества нашего
          Коворкинг-центра
       </h4>
     </div>
     <div class="left">
       <img src="~assets/imgs/left.png" alt="Left Bg image">
     </div>
     <div class="right">
       <img src="~assets/imgs/right.png" alt="Right Bg image">
     </div>
     <div class="container">
       <!-- First row -->
       <div class="row main_functions">
         <div class="col-sm-4 main_item">
           <div class="text-center">
             <nuxt-link to="#">
               <img src="~assets/imgs/internet.png" alt="Image">
             </nuxt-link>
           </div>
           <div>
             <p class="img_txt text-center ">
                Быстрый, беспроводной интернет
                нового поколения без лимитов и ограничения трафика
             </p>
           </div>
         </div>
         <div class="col-sm-4 main_item">
           <div class="text-center">
             <nuxt-link to="#">
               <img src="~assets/imgs/study.png" alt="Image">
             </nuxt-link>
           </div>
           <div>
             <p class="img_txt text-center">
                 Ежедневное обучение происходит за счет 
                 знакомства с новыми людьми
             </p>
           </div>
         </div>
         <div class="col-sm-4 main_item">
           <div class="text-center">
             <nuxt-link to="#">
               <img src="~assets/imgs/ad.png" alt="Image">
             </nuxt-link>
           </div>
           <div>
             <p class="img_txt text-center">
                Возможность продвигать и рекламировать свои услуги
                потенциальным заказчикам
             </p>
           </div>
         </div>
       </div>
       <!-- Second row -->
       <div class="row">
         <div class="col-sm-4 main_item">
           <div class="text-center">
             <nuxt-link to="#">
               <img src="~assets/imgs/meet.png" alt="Image">
             </nuxt-link>
           </div>
           <div>
             <p class="img_txt text-center">
                Место для встречи с клиентами, руководителями
                и специалистами
             </p>
           </div>
         </div>
         <div class="col-sm-4 main_item">
           <div class="text-center">
             <nuxt-link to="#">
               <img src="~assets/imgs/hakaton.png" alt="Image">
             </nuxt-link>
           </div>
           <div>
             <p class="img_txt text-center">
                  Возможность проведения различных
                  презентаций, мастер-классов и  хакатонов
             </p>
           </div>
         </div>
         <div class="col-sm-4 main_item">
           <div class="text-center">
             <nuxt-link to="#">
               <img src="~assets/imgs/technology.png" alt="Image">
             </nuxt-link>
           </div>
           <div>
             <p class="img_txt text-center">
               Использование техники и технологий 
               (специализированный софт, оборудование, 3Д-принтеры)
             </p>
           </div>
         </div>
       </div>
     </div>
   </div>
 </section>
 <section>
   <div class="content4">
     <div class="help_txt">
       <h2 class="text4 text-center">
        <span class="i">i</span><span class="work">work</span> — <span class="help">
          поможет </span> Вам
          найти нужных людей
       </h2>
     </div>
   </div>
 </section>
 <section> 
   <tarifs />
 </section>
 <section>
   <Map />
 </section>
 </div>
</template>
<script>
export default {
  data() {
      return {
        swiperOption: {
          slidesPerView: 1,
          spaceBetween: 30,
          autoplay: { delay: 5000 },
          keyboard: { enabled: true },
          loop: true,
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          },
          navigation: {
            nextEl: '.swiper-button-next',
            prevEl: '.swiper-button-prev'
          }
        }
      }
    }
 
  }
</script>

<style scoped>
body{
  overflow-x: hidden;
}
.banner{
  background-color: rgb(234, 182, 18);
  width: 100%;
  height: 925px;
  position: relative;
}
.banner_txt{
  background-image: url('~assets/imgs/banner.png');
  position: absolute;
  z-index: 10;
  width: 100%;
  height: 600px;
  text-align: center;
  padding-top: 100px;
}
.txt{
  height: 98px;
  text-align: center;
  width: 800px;
  margin: auto;
  
}
.txt p{
  color: white;
}
.book_rect{
  /* Style for "Rounded Re" */
width: 274px;
height: 56px;
box-shadow: 0 3px 0 #272727;
border-radius: 28px;
background-color: #2ebd7f;
padding-top: 15px;
margin: auto;
}
.book{
width: 180px;
height: 16px;
color: #ffffff;
font-family: "Open Sans";
font-size: 20px;
font-weight: 700;
line-height: 27.22px;
text-transform: uppercase;
}
.book_rect a{
  text-decoration: none;
}
.section2{
  position: relative;
  display: flex;
}
.slider{
  /* Style for "Photo" */
width: 1099px;
height: 848px;
display: inline-block;
}
.right_content{
display: inline-block;
padding-top: 150px;
flex: 1;
}
.logo1{
  text-align: center;
}
.logo_title{
height: 29px;
color: #272727;
font-family: "Open Sans";
font-size: 30px;
font-weight: 400;
line-height: 59.25px;
margin-bottom: 20px;
}
.logo_div{
  width: 625px;
  margin: auto;
}
.logo_text{
  height: 119px;
  color: #272727;
  font-family: "Open Sans";
  font-size: 16px;
  font-weight: 400;
  line-height: 25.67px;
}
.resident{
width: 189px;
height: 37px;
border-radius: 19px;
border: 2px solid #2ebd7f;
margin: auto;
text-align: center;
}
.resident a{
  text-decoration: none;
}
.resident_txt{
color: #2ebd7f;
font-family: "Open Sans";
font-size: 14px;
font-weight: 700;
line-height: 35px;
text-transform: uppercase;
}
.content3{
  width: 100%;
  height: 643px;
  background-color: #f9f9f9;
  padding-top: 30px;
}
.left{
  position: absolute;
  z-index: 0;
  left: 0px;
}
.right{
  position: absolute;
  z-index: 0;
  right: 0px;
}
.main_functions{
  margin-top: 50px;
}
.main_item{
  margin-bottom: 50px;
}
/* Fourth Section */
.content4{
background: url('~assets/imgs/bg4.png');
width:100%;
height: 367px;
background-color: rgba(39, 39, 39, 0.76);
padding-top: 130px;
}
.text4{
height: 112px;
color: #fefefe;
font-family: "Open Sans - Semibold";
font-size: 50px;
font-weight: 400;
line-height: 65px;
text-transform: uppercase;
}
.i{
  color: #eeba11;
  letter-spacing: 0.05px;
}
.work{
  color: #eeba11;
  letter-spacing: 0.05px;
}
.help{
  letter-spacing: 0.05px;
}
.help_txt{
  width: 626px;
  margin: auto;
}



</style>