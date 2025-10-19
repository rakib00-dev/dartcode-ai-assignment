<script setup>
  defineProps({
    title: String,
  });
</script>

<template>
  <button
    class="text-sm md:text-md border border-gray-400 rounded-md py-1 px-4 capitalize cursor-pointer"
  >
    {{ title }}
  </button>
</template>
