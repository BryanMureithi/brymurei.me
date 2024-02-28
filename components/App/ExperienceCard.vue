<template>
    <div class="flex items-center mt-10 space-x-6">
        <div class="h-28 w-0.5 bg-gray-400 rounded-xl"></div>
        <div>
            <h2>{{ experience.title }}</h2>
            <p class="mt-2 text-sm text-gray-600 dark:text-gray-400">{{ experience.organisation }} . {{ experience.period }}</p>
            <p class="mt-2 text-sm text-gray-600 dark:text-gray-400">{{ experience.description }}</p>
        </div>
    </div>
</template>

<script setup>
defineProps({
  experience: {
    type: Object,
    required: true,
  },
});
</script>