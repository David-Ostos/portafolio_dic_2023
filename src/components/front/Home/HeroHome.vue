<script setup lang="ts">
import ButtonPrimary from '@/components/front/components/materials/buttonPrimary.vue'

</script>

<template>
  <section class="bg-white dark:bg-gray-900">
    <div class=" flex flex-col md:grid max-w-screen-xl gap-5 px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12">
        <div class="mr-auto place-self-center lg:col-span-7">
            <h1 class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white">Desarrollo de Paginas Web</h1>
            <p class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400">From checkout to global sales tax compliance, companies around the world use Flowbite to simplify their payment stack.</p>
            <a href="#" class="inline-flex items-center justify-center px-5 py-3 mr-3 text-base font-medium text-center text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900">
                Get started
                <svg class="w-5 h-5 ml-2 -mr-1" fill="rgb(74 222 128)" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
            </a>
            <ButtonPrimary name="Speak to Sales" />
        </div>
        <img
          src="https://i.imgur.com/18Fy4NI.jpg"
          alt="avatar"
          class=" md:col-start-4 lg:col-start-9 col-span-3 inline-block relative object-cover object-center !rounded-full mx-auto w-2/4 h-2/4 md:w-40 md:h-40 lg:w-full lg:h-full border-2 border-green-500 p-1"
        />              
    </div>
  </section>
</template>