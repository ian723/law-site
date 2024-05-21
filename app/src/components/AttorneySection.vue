<template>
  <section class="bg-orange-50 py-16 lg:py-20">
    <!-- Hero -->
    <div class="max-w-7xl mx-auto p-4 sm:p-6 lg:p-8">
      <!-- Text Section -->
      <div class="max-w-xl mx-auto text-center py-14">
        <h2
          class="text-2xl leading-tight text-black sm:text-2xl lg:text-4xl uppercase font-serif"
        >
          Meet our most talented and qualified attorneys
        </h2>
      </div>
      <!-- Grid -->
      <div class="grid md:grid-cols-2 gap-4 md:gap-8 xl:gap-20 md:items-center">
        <div>
          <h1
            class="text-xl text-gray-800 sm:text-2xl lg:text-4xl uppercase leading-tight font-serif"
          >
            Lead Counsel Verified Attorneys
          </h1>
          <p class="mt-3 text-lg text-gray-800">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro et
            ipsa reiciendis, quas voluptatibus nulla beatae modi? Sapiente,
            voluptatem illum.
          </p>

          <!-- Link -->
          <div class="mb-7 sm:mt-7">
            <a
              class="text-xl font-semibold text-orange-700 underline underline-offset-4"
              href="#"
            >
              Learn More
            </a>
          </div>
        </div>
        <!-- End Col -->

        <div class="mx-auto relative">
          <img
            class="w-72 lg:w-full"
            src="https://images.pexels.com/photos/5668777/pexels-photo-5668777.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            alt="Image Description"
          />
          <!-- Floating card -->
          <span
            class="absolute -top-8 -left-8 h-32 w-32 sm:h-40 sm:w-40 bg-gray-100 rounded-xl"
          >
            <!-- Circle and Text -->
            <div
              class="flex flex-col p-2 justify-center items-center pb-3 h-full"
            >
              <span
                class="h-12 w-12 sm:h-16 sm:w-16 border-4 rounded-full border-orange-700"
              ></span>
              <p
                class="pt-3 text-sm sm:text-lg font-semibold tracking-wide text-center"
              >
                Legal Solution
              </p>
            </div>
          </span>
          <!-- Floating Card -->
          <span
            class="absolute top-40 lg:top-56 -right-8 h-32 w-32 sm:h-40 sm:w-40 rounded-xl bg-gray-100"
          >
            <!-- Circle and Text -->
            <div
              class="flex flex-col p-2 justify-center items-center pb-3 h-full"
            >
              <span
                class="h-12 w-12 sm:h-16 sm:w-16 border-4 rounded-full border-orange-700"
              ></span>
              <p
                class="pt-3 text-sm sm:text-lg font-semibold tracking-wide text-center"
              >
                Project Success
              </p>
            </div>
          </span>
          <!-- Floating card -->
          <span
            class="absolute -bottom-8 -left-8 h-36 w-36 sm:h-40 sm:w-40 rounded-xl bg-gray-100"
          >
            <!-- Circle and Text -->
            <div
              class="flex flex-col p-2 justify-center items-center pb-3 h-full"
            >
              <span
                class="h-12 w-12 sm:h-16 sm:w-16 border-4 rounded-full border-orange-700"
              ></span>
              <p class="font-bold text-xl py-1">500+</p>
              <p
                class="text-sm sm:text-lg font-semibold tracking-wide text-center"
              >
                Projects Done
              </p>
            </div>
          </span>
        </div>
        <!-- End Col -->
      </div>
      <!-- End Grid -->
    </div>
    <!-- End Hero -->
  </section>
</template>

<script setup></script>

<style lang="scss" scoped></style>
