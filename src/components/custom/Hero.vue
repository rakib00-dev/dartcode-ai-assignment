<script setup>
  import HeroBgLineEelement from "../common/HeroBgLineEelement.vue";
  import LargeButton from "../common/LargeButton.vue";
</script>

<template>
  <section>
    <div class="baseContainer grid gap-20 overflow-hidden">
      <div class="grid gap-6 place-items-center">
        <h1
          class="text-3xl md:text-5xl lg:text-6xl text-center grid font-[400] leading-[54px] md: lg:leading-[84px]"
        >
          Accelerate Your Development & QA Workflow with
          <span class="text-[var(--primary-color)] font-[700]"
            >AI-Powered Automation</span
          >
        </h1>
        <div class="grid gap-8 place-items-center">
          <div class="relative grid place-items-center">
            <HeroBgLineEelement class="w-full absolute -z-10 max-md:hidden" />
            <p class="text-center w-1/2">
              DartCode AI streamlines your QA and release processes by
              automating pull request management, coordinating multi-repository
              operations, and enhancing quality assurance.
            </p>
          </div>
          <div class="flex justify-center items-center">
            <LargeButton
              -custom-class="bg-[var(--primary-color)] text-white hover:bg-[var(--primary-dark-color)] hover:font-medium px-4"
              padding-x
              title="get started"
            />
          </div>
          <span> Explore <a href="#">DartCode AI for free.</a></span>
        </div>
      </div>
      <div class=""></div>
    </div>
  </section>
</template>
