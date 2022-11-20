<template>
  <section>
    <!--    Container-->
    <div class="container">
      <!--      Swiper-->
      <swiper
          :modules="modules"
          :slides-per-view="1"
          :space-between="50"
          navigation
          @swiper="onSwiper"
          @slideChange="onSlideChange"
      >
        <!--        BorutoScreen-->
        <swiper-slide class="boruto_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 70 [ENG]</h3>
              <h3>Boruto: Naruto Next Generations</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/images/boruto.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        BorutoScreen-->
        <!--        OnePieceScreen-->
        <swiper-slide class="onepiece_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--          MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--          MainScreenTitle-->
            <!--          MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 1064 [ENG]</h3>
              <h3>One Piece</h3>
            </div>
            <!--          MainScreenInfo-->
            <!--          MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--          MainScreenDesc-->
            <!--          MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--          MainScreenActions-->
            <!--          MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--          MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--          MainScreenBtn-->
              <!--          MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--          MainScreenBtn-->
            </div>
            <!--          MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/images/one_pie.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        OnePieceScreen-->
        <!--        TokyoScreen-->
        <swiper-slide class="tokyo_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 127 [ENG]</h3>
              <h3>Tokyo Revengers</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/images/tokyo_ravengers.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        TokyoScreen-->
        <!--        OnePunchManScreen-->
        <swiper-slide class="onepucnch_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 182 [ENG]</h3>
              <h3>One Punch Man</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/images/one_punchmen.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
        <!--        SpyScreen-->
        <swiper-slide class="spy_screen">
          <!--          MainScreenTexts-->
          <div class="main_screen_texts">
            <!--            MainScreenTitle-->
            <div class="main_screen_title">
              <h1>HOT MANGA READING</h1>
            </div>
            <!--            MainScreenTitle-->
            <!--            MainScreenInfo-->
            <div class="main_screen_info">
              <h3>Chapter: 4 [ENG]</h3>
              <h3>Spy x Family</h3>
            </div>
            <!--            MainScreenInfo-->
            <!--            MainScreenDesc-->
            <div class="main_screen_desc">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. A, urna netus dolor egestas viverra aliquam
                nisi
                volutpat vulputate. Aliquet orci...</p>
            </div>
            <!--            MainScreenDesc-->
            <!--            MainScreenActions-->
            <div class="main_screen_actions">
              <div class="actions df">
                <div class="action">
                  <p>Actions</p>
                </div>
                <div class="action">
                  <p>Adventure</p>
                </div>
                <div class="action">
                  <p>Martial Arts</p>
                </div>
                <div class="action">
                  <p>Shounen</p>
                </div>
                <div class="action">
                  <p>Super Power</p>
                </div>
              </div>
            </div>
            <!--            MainScreenActions-->
            <!--            MainScreenBtns-->
            <div class="main_screen_btns df">
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="read_now cursor">
                  Read Now
                </button>
              </div>
              <!--            MainScreenBtn-->
              <!--            MainScreenBtn-->
              <div class="main_screen_btn">
                <button type="submit" class="view_info cursor">
                  View Info
                </button>
              </div>
              <!--            MainScreenBtn-->
            </div>
            <!--            MainScreenBtns-->
          </div>
          <!--          MainScreenTexts-->
          <!--          MainScreenImg-->
          <div class="main_screen_img">
            <img src="../assets/images/spyxfamily.png" alt="">
          </div>
          <!--          MainScreenImg-->
        </swiper-slide>
      </swiper>
      <!--      Swiper-->
    </div>
    <!--    Container-->
  </section>
</template>

<script>
import {Navigation, A11y} from 'swiper';

import {Swiper, SwiperSlide} from 'swiper/vue'


import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';


export default {
  name: "MainScreen",
  components: {
    Swiper,
    SwiperSlide
  },
  setup() {
    const onSwiper = (swiper) => {
      // console.log(swiper)
    };
    const onSlideChange = () => {
      // console.log('slide change')
    };
    return {
      onSwiper,
      onSlideChange,
      modules: [Navigation,  A11y],
    };
  }
}
</script>

<style scoped>

.boruto_screen {
  background-image: url("../assets/images/main_screen_bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  border-radius: 10px;
  margin-top: 30px;
  display: flex;
}
.onepiece_screen {
  background-image: url("../assets/images/one_pie_bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  border-radius: 10px;
  margin-top: 30px;
  display: flex;
}
.tokyo_screen {
  background-image: url("../assets/images/tokyo_ravengers_bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  border-radius: 10px;
  margin-top: 30px;
  display: flex;
}
.onepucnch_screen {
  background-image: url("../assets/images/one_punchmen_bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  border-radius: 10px;
  margin-top: 30px;
  display: flex;
}
.spy_screen {
  background-image: url("../assets/images/spyxfamily_bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  border-radius: 10px;
  margin-top: 30px;
  display: flex;
}
.swiper-button-next:after, .swiper-button-prev:after {
  font-size: 24px;
  color: #111111;
  font-weight: 800;
}
.main_screen_texts {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-direction: column;
  margin-left: 47px;
}

.main_screen_title h1 {
  font-family: 'Gilroy-Heavy', sans-serif;
  font-size: 73px;
  line-height: 91px;
  letter-spacing: -0.055em;
  color: #FFFFFF;
  width: 397px;
  margin-top: 69px;
  text-align: left;
}

.main_screen_info {
  margin-top: 40px;
}

.main_screen_info h3 {
  padding-top: 10px;
  font-family: 'Gilroy-Bold', sans-serif;
  font-size: 32px;
  line-height: 40px;
  color: #FFFFFF;
  text-align: left;
}

.main_screen_desc p {
  font-family: 'Gilroy-Medium';
  font-size: 18px;
  line-height: 22px;
  width: 421px;
  color: #FFFFFF;
  margin-top: 15px;
  text-align: left;
}

.action:nth-child(1) {
  margin-left: 0px;
}

.action {
  width: 80px;
  height: 38px;
  border: 1px solid #FFFFFF;
  border-radius: 4px;
  margin-top: 20px;
  margin-left: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.action:nth-child(3) {
  width: 104px;
}

.action:nth-child(5) {
  width: 111px;
}

.action p {
  font-family: 'Gilroy-Medium';
  font-size: 14px;
  line-height: 17px;
  color: #FFFFFF;
}

.main_screen_btns {
  margin-top: 40px;
}

.read_now {
  width: 156px;
  height: 48px;
  border-radius: 5px;
  border: none;
  background: #FCE155;
  font-family: 'Gilroy-Medium';
  font-size: 18px;
  line-height: 22px;
  color: #111111;
}

.view_info {
  width: 156px;
  height: 48px;
  background: #FFFFFF;
  border-radius: 5px;
  border: none;
  margin-left: 10px;
  font-family: 'Gilroy-Medium';
  font-size: 18px;
  line-height: 22px;
  color: #111111;
}

.swiper-button-next {
  right: 35px;
  top: auto;
  bottom: 60px;
}

.swiper-button-prev {
  right: 145px;
  top: auto;
  bottom: 60px;
}

.swiper-button-next, .swiper-button-prev {
  width: 70px;
  height: 70px;
  border-radius: 50%;
  text-align: center;
  background: #fff;
  color: #111;
  display: flex;
  justify-content: center;
  align-items: center;
}
.swiper-button-next {
  position: absolute;
  top: 85% !important;
}
.main_screen_img {
  margin-left: 78px;
}
</style>