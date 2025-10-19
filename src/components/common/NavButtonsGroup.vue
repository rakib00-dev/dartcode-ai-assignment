<script setup>
  import LargeButton from "./LargeButton.vue";
</script>

<template>
  <div class="hidden lg:flex justify-center items-center gap-5">
    <LargeButton
      title="Login"
      -custom-class="hover:font-medium hover:bg-[var(--primary-color)] hover:text-white md:px-12 text-[var(--primary-color)] outline-[var(--primary-color)]"
    />
    <LargeButton
      title="Signup"
      -custom-class="bg-[var(--primary-color)] text-white hover:bg-[var(--primary-dark-color)] hover:font-medium md:px-12"
    />
  </div>
</template>
