<template>
  <div class=" bg-white px-6 pt-16 lg:pt-40 sm:px-10 md:px-20 lg:px-40 gap-y-[120px] flex flex-col">
    <div class="flex flex-col max-w-7xl lg:flex-row lg:gap-16 xl:gap-32">
      <div class=" lg:w-1/2">
        <img
            src="/public/assets/product-yx1-earphones/desktop/image-category-page-preview.jpg"
            alt=""
            class="rounded-lg w-full h-auto object-cover pb-8"
        >
      </div>
      <div
          class="text-center text-black flex flex-col gap-6 lg:text-start lg:w-1/2 lg:max-w-[445px] lg:transform lg:translate-y-10 lg:gap-0">
        <h1 class="text-hov tracking-[10px] uppercase text-sm pt-8">
          New Product
        </h1>
        <p class="text-[28px] sm:text-[32px] tracking-wider font-bold lg:text-4xl lg:tracking-[1.43px] lg:pt-4 lg:pb-8">
          YX1 WIRELESS
          EARPHONES
        </p>
        <h2 class="opacity-50 text-[15px] leading-[25px] font-medium lg:pb-10">
          Tailor your listening experience with bespoke dynamic drivers
          from the new YX1 Wireless Earphones. Enjoy incredible high-fidelity
          sound even in noisy environments with its active noise cancellation feature.
        </h2>
        <div>
          <button
              class="bg-hov text-white py-3 hover:bg-[#FBAF85] px-7 tracking-wide sm:w-auto hover:bg-opacity-90 transition-colors duration-300 text-[13px]">
            <RouterLink to="/EarphonePr1">SEE PRODUCT</RouterLink>
          </button>
        </div>

      </div>
    </div>

    <div class="pt-10">
      <image-cpt/>
    </div>

  </div>

  <div class="px-6 py-40 sm:px-10 md:px-20 lg:px-40 ">
    <textImg/>
  </div>


</template>

<script setup>
// Vous pouvez ajouter ici la logique du composant si nécessaire
import ImageCpt from "@/components/imageCpt.vue";

import textImg from "@/components/text&Img.vue";
</script>
