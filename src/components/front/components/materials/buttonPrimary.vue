<script setup lang="ts">
const props = defineProps({
  name: String
  })
</script>

<template>
    <a class="inline-flex px-5 py-3 mx-auto text-base font-medium text-center text-gray-900 border
     border-green-400 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white
     dark:border-green-400 dark:hover:bg-gray-700 dark:focus:ring-gray-800"
    >{{ name }}</a>
</template>