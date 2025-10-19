<script setup lang="ts">
  import WhatCanIHelpImage from "../common/WhatCanIHelpImage.vue";
</script>

<template>
  <section class="py-20">
    <div class="baseContainer grid gap-16">
      <div class="grid place-items-center gap-4">
        <h1 class="mainSectionHeader">Explore DartCode AI Features</h1>
      </div>

      <div
        class="flex max-lg:justify-start justify-between max-lg:gap-6 max-lg:flex-col items-center"
      >
        <div class="grid max-lg:place-items-start gap-6 w-full">
          <div>
            <h5 class="text-2xl font-medium">Modular & Scalable</h5>
            <p class="text-lg text-gray-400 font-[400]">
              Use one module or all — no monoliths here.
            </p>
          </div>
          <div>
            <h5 class="text-2xl font-medium">Dart-Specific AI Intelligence</h5>
            <p class="text-lg text-gray-400 font-[400]">
              Fine-tuned for Dart codebases, not generic LLM bloat.
            </p>
          </div>
          <div>
            <h5 class="text-2xl font-medium">Feedback Loops Built In</h5>
            <p class="text-lg text-gray-400 font-[400]">
              The more you use it, the smarter it gets.
            </p>
          </div>
          <div>
            <h5 class="text-2xl font-medium">CLI + Dashboard Views</h5>
            <p class="text-lg text-gray-400 font-[400]">
              For builders who love the terminal and teams who need visibility.
            </p>
          </div>
          <div>
            <h5 class="text-2xl font-medium">
              GitHub/GitLab/Bitbucket Integration
            </h5>
            <p class="text-lg text-gray-400 font-[400]">
              OAuth-ready and secure from day one.
            </p>
          </div>
        </div>
        <div><WhatCanIHelpImage class="" /></div>
      </div>
    </div>
  </section>
</template>
