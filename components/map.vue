<template>
    <div>
       <div class="map-main">
            <div class="map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7128.140980412638!2d69.33945957846446!3d41.30855689711017!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38aef5a583af854f%3A0xe60eed94d6778af5!2sGround+Zero!5e0!3m2!1sru!2s!4v1561629263731!5m2!1sru!2s"
             width="100%" height="600" frameborder="0" style="border:0" allowfullscreen></iframe>
            <div class="map_card">
                <div class="map-card__inner">
                    <div class="map-item">
                        <div class="map-icon">
                            <img src="~assets/imgs/location.png" alt="Image">
                        </div>
                        <div class="icon_text">
                            <h5>
                                Ташкент, Яшнободский район,
                                ул. Темура Малика (Аэродромная), 146
                            </h5>
                        </div>
                    </div>

                    <div class="map-item">
                        <div class="map-icon">
                            <img src="~assets/imgs/phone.png" alt="Image">
                        </div>
                        <div class="icon_text">
                            <h5>
                                8 (71) 269 93 39
                                +998 (90) 938 78 77 
                            </h5>
                        </div>
                    </div>

                    <div class="map-item">
                        <div class="map-icon">
                            <img src="~assets/imgs/clock.png" alt="Image">
                        </div>
                        <div class="icon_text">
                            <h5>
                                7 дней в неделю
                                с 9:00 - до 20:00
                            </h5>
                        </div>
                    </div>

                    <div class="map-item">
                        <div class="map-icon">
                            <img src="~assets/imgs/document.png" alt="Image">
                        </div>
                        <div class="icon_text">
                            <h5>
                                events@technoplaza.uz
                            </h5>
                        </div>
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

.map-main {
    position: relative;

}

.map_card{
position: absolute;
background: url('~assets/imgs/contact.png');
background-size: cover;
width: 500px;
height: 391px;
box-shadow: -4px 4px 0 rgba(0, 0, 0, 0.22);
border-radius: 10px;
z-index: 500;
right: 10px;
top: 50%;
transform: translateY(-50%);
}

.map-item {
    display: flex;
    align-items: center;
    justify-content: center;
    /* flex-wrap: wrap; */
    margin-top: 15px;
    margin-block: 15px;
    
}

.map-item h5 {
    color: #fff;
}

.map-icon {
    width: 100px!important;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #eab612;
    border-radius: 50%;
    margin-right: 20px;
}

.map-icon img {
    width: 30px;
    height: 30px;

}

.map-card__inner {
    position:relative;
    z-index: 550;
    margin-left: -30px;
}
.icon_text{
    width: 600px;
}

</style>
