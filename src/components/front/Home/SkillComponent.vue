<template>
  <section class="py-14  dark:bg-gray-900">
    <div class="max-w-screen-xl mx-auto px-4 text-center text-gray-400 md:px-8">
      <div class="max-w-2xl mx-auto">
        <h3 class="text-gray-400 dark:text-white text-3xl font-semibold sm:text-4xl">
          The fastest way to launch a product
        </h3>
        <p class="mt-3">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus.
        </p>
      </div>
      <div class="mt-12">
        <ul class="grid gap-y-8 gap-x-12 sm:grid-cols-2 lg:grid-cols-3">
          <li v-for="(item, index) in features" :key="index" class="space-y-3">
            <div class="w-12 h-12 mx-auto bg-indigo-50 text-indigo-600 rounded-full flex items-center justify-center">
              <i :class="item.icon"></i>

            </div>
            <h4 class="text-lg dark:text-white font-semibold">
              {{ item.title }}
            </h4>
            <p>
              {{ item.desc }}
            </p>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">

      let features = [
        {
            icon: "fa-brands fa-html5",
            title: "Fast Refresh",
            desc: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus."
        },
        {
            icon: "",
            title: "Analytics",
            desc: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus."
        },
        {
            icon: "",
            title: "Datacenter security",
            desc: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus."
        },
        {
            icon: "",
            title: "Build on your terms",
            desc: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus."
        },
        {
            icon: "",
            title: "Safe to use",
            desc: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus."
        },
        {
            icon: "",
            title: "Flexible",
            desc: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius, enim ex faucibus purus."
        },
      ]
</script>