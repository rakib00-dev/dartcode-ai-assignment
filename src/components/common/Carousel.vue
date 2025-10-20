<script setup>
  import { Swiper, SwiperSlide } from "swiper/vue";

  import "swiper/css";
  import "swiper/css/pagination";

  import { Pagination } from "swiper/modules";
  import PlanCard from "./PlanCard.vue";

  const modules = [Pagination];
</script>

<template>
  <div class="w-full py-10">
    <swiper
      :slides-per-view="'auto'"
      :space-between="30"
      :pagination="{ clickable: true }"
      :modules="modules"
      class="mySwiper"
    >
      <swiper-slide v-for="n in 3" :key="n" class="" style="width: 80%">
        <PlanCard />
      </swiper-slide>
      <swiper-slide v-for="n in 3" :key="n" class="" style="width: 80%">
        <PlanCard
          is-popular
          small-title="Enhance Plan"
          :card-list-texts="[
            'AI Documentation Module',
            'AI CLI for Dart',
            'AI QA Testing',
          ]"
        />
      </swiper-slide>
      <swiper-slide v-for="n in 3" :key="n" class="" style="width: 80%">
        <PlanCard
          small-title="Enterprise Plan"
          :card-list-texts="[
            'AI Documentation Module',
            'AI CLI for Dart',
            'AI QA Testing',
            'AI Release Management',
          ]"
        />
      </swiper-slide>
    </swiper>
  </div>
</template>

<style>
  .mySwiper {
    width: fit-content;
    height: 100%;
    padding-bottom: 3rem;
  }

  .swiper-pagination-bullet {
    background-color: #999;
    opacity: 0.6;
  }
  .swiper-pagination-bullet-active {
    background-color: #2563eb;
    opacity: 1;
  }
</style>
