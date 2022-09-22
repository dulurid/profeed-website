<template>
  <swiper
    :effect="'coverflow'"
    :grabCursor="true"
    :slidesPerView="'auto'"
    :coverflowEffect="{
      rotate: 50,
      stretch: 0,
      depth: 100,
      modifier: 1,
      slideShadows: false,
    }"
    :pagination="{
      dynamicBullets: true,
    }"
    :modules="modules"
    class="mySwiper"
  >
    <swiper-slide>
      <img v-motion v-bind="motion(300)" src="/img/img_1.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(350)" src="/img/img_2.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(400)" src="/img/img_3.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(500)" src="/img/img_4.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(600)" src="/img/img_1.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(700)" src="/img/img_2.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(800)" src="/img/img_3.png" />
    </swiper-slide>
    <swiper-slide>
      <img v-motion v-bind="motion(900)" src="/img/img_4.png" />
    </swiper-slide>
  </swiper>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/effect-coverflow";
import "swiper/css/pagination";

// import required modules
import { EffectCoverflow, Pagination } from "swiper";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    const motion = (delay) => {
      return {
        initial: {
          y: 100,
          opacity: 0,
        },
        visibleOnce: {
          y: 0,
          opacity: 1,
          transition: {
            delay: delay,
          },
        },
      };
    };
    return {
      motion,
      modules: [EffectCoverflow, Pagination],
    };
  },
};
</script>

<style>
.swiper {
  width: 100%;
  padding-top: 50px;
  padding-bottom: 50px;
}

.swiper-slide {
  background-position: center;
  background-size: cover;
  width: 300px;
  height: 400px;
  border-radius: 20px;
}

.swiper-slide img {
  display: block;
  width: 100%;
}
</style>
