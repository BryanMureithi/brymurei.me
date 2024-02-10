<template>
  <div class="space-y-6">
    <NuxtImg
      src="/avatar.JPG"
      alt="Fayaz Ahmed"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px"
      placeholder
      format="webp"
    />
    <h1
      class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100"
    >
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Bryan, I work as a software, product engineer and designer from
      Nairobi, Kenya. Welcome to my creative haven, where the art of user
      experience collides with the magic of fullstack development. I am
      passionate about crafting digital journeys that seamlessly blend
      aesthetics and functionality. Join me on a visual and technical adventure that showcases the harmonious
      synergy of a UI/UX designer and fullstack developer.
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      I specialize in
      building web applications and sites using Javascript, React, Vue &amp;
      Node. I've procrastinated building this website for years but finally it's
      here, I've carved out my own little nook on the internet to share my silly
      experiments, nifty projects, and thoughts (mostly about tech and design).
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a Fullstack Developer at
      <a href="https://www.sortseam.com/" target="_blank" class="underline"
        >Sortseam</a
      >, and by night (and weekends), I'm busy tinkering with some random tool
      or app that I am building.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Bryan Mureithi",
  description:
    "I'm Bryan, a UI/UX Designer and Software Developer from Nairobi, Kenya. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>
