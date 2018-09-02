<template lang="html">
    <section :class="cname">
        <swiper>
            <swiper-slide>a</swiper-slide>
        </swiper>
    </section>
</template>

<script>
import { swiper, swiperSlide } from "vue-awesome-swiper";
export default {
  props: {
    cname: {
      type: String,
      default: ""
    }
  },
  components: {
    swiper,
    swiperSlide
  }
};
</script>

<style lang="scss">
@import "~swiper/dist/css/swiper.css";
</style>
