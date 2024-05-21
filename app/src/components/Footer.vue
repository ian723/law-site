<template>

  <div class="font-serif">
    <!-- footer first part -->

    <div
      class="flex flex-col justify-center items-center bg-orange-50 space-y-8 py-12"
    >
      <div class="sm:pr-40">
        <h3 class="font-bold leading-9 text-5xl tracking-wide px-16">
          WHAT A LAWYER
        </h3>
      </div>
      <div class="flex justify-center items-center space-x-8">
        <button class="border border-black p-4 hover:bg-black hover:text-orange-50">
           <router-link to="/_blank">Contact Us</router-link>
          
        </button>
        <div>
          <div class="flex items-center">
            <div class="hidden sm:flex sm:w-[50px] sm:h-[1px] sm:bg-black rounded-lg"></div>
            <p class="hidden sm:flex pb-[1px]">></p>
            <p class="px-4">LETS TALK</p>
          </div>
        </div>
      </div>
      <div class="sm:pl-36 text-3xl tracking-tighter mb-7">
        <p>HELLO@OFSPACE.CO</p>
      </div>
      <div class="flex bg-gray-400 w-[1000px] h-[1px]"></div>
    </div>
    <!-- <hr> -->
    <!-- footer lower part -->
    <div
      class="flex flex-col space-y-12 md:flex-row justify-between items-center bg-orange-50 px-5 py-12"
    >
      <div class="px-5 md:pt-12">
        <h3>FLORISITY</h3>
      </div>
      <div class="">
        <ul class="flex">
          <li class="px-4"><router-link to="/">Home</router-link></li>
          <li class="px-4"><router-link to="/project">Project</router-link></li>
          <li class="px-4"><router-link to="/blog">Blog</router-link></li>
          <li class="px-4"><router-link to="/_blank">Contact</router-link></li>
        </ul>
      </div>
      <div class="grid grid-cols-1 px-5">
        <p class="text-right">2024 designed by OfspacE LLC</p>
        <div class="flex justify-end items-end space-x-1">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-c-circle mb-1"
            viewBox="0 0 16 16"
          >
            <path
              d="M1 8a7 7 0 1 0 14 0A7 7 0 0 0 1 8m15 0A8 8 0 1 1 0 8a8 8 0 0 1 16 0M8.146 4.992c-1.212 0-1.927.92-1.927 2.502v1.06c0 1.571.703 2.462 1.927 2.462.979 0 1.641-.586 1.729-1.418h1.295v.093c-.1 1.448-1.354 2.467-3.03 2.467-2.091 0-3.269-1.336-3.269-3.603V7.482c0-2.261 1.201-3.638 3.27-3.638 1.681 0 2.935 1.054 3.029 2.572v.088H9.875c-.088-.879-.768-1.512-1.729-1.512"
            />
          </svg>
          <p class="text-right">powered by Ofspace LLC</p>
        </div>
        
      </div>
    </div>
  </div>

</template>

<script setup></script>

<style lang="scss" scoped></style>
