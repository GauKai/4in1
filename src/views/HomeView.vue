<script setup>
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <div class="flex w-full h-screen flex-col md:flex-row">
      <nav class="flex md:flex-col w-full h-[100px] md:w-[366px] md:h-screen bg-red-100 shrink-0 justify-between md:justify-normal px-[20px] md:px-[0px] items-center gap-y-[30px] text-center leading-[50px]">
        <div class="w-[50px] h-[50px] md:w-[150px] md:h-[150px] bg-amber-200 md:mt-[80px]"></div>
        <a href="#" class="w-[100px] md:h-[50px] bg-amber-200 hover:bg-amber-400">123</a>
        <a href="#" class="w-[100px] md:h-[50px] bg-lime-200 hover:bg-lime-400">123</a>
        <a href="#" class="w-[100px] md:h-[50px] bg-sky-200 hover:bg-sky-400">123</a>
      </nav>

      <div class="flex grow justify-center items-center">
        <div class="w-[960px] h-[570px]">
          <div class="flex flex-col sm:flex-row flex-wrap xl:flex-nowrap h-full w-full xl:gap-x-[10px] lg:gap-y-[10px] ">
            <div class="w-full h-1/3 sm:w-1/2 sm:h-1/2 xl:w-1/3 xl:h-full bg-amber-200"></div>
            <div class="w-full h-1/3 sm:w-1/2 sm:h-1/2 xl:w-1/3 xl:h-full bg-lime-200"></div>
            <div class="w-full h-1/3 sm:w-full sm:h-1/2 xl:w-1/3 xl:h-full bg-sky-200"></div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
