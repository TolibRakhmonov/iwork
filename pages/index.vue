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
 <section>
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
   <div>

   </div>
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
.slider{
  /* Style for "Photo" */
width: 1099px;
height: 848px;
}

</style>