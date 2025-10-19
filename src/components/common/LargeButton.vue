<script setup>
  defineProps({
    title: {
      type: String,
      required: true,
    },
    CustomClass: String,
    paddingX: {
      default: "px-8",
      type: String,
    },
    href: {
      default: "#",
      type: String,
    },
  });
</script>

<template>
  <a
    :href="href"
    :class="[
      'transition-all duration-300 text-sm md:text-md outline-[1.5px] outline-[var(--primary-color)] rounded py-2 capitalize cursor-pointer w-fit',
      CustomClass,
    ]"
  >
    {{ title }}
  </a>
</template>

<style></style>
