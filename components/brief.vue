<template>
  <div class="xl:px-70 lg:px-36 md:px-20 px-10 text-skin-primary overflow-hidden">
    <!-- <h1 class="text-3xl font-bold pt-10">The Brief</h1> -->
    <div class="brief">
      <div class="image">
        <slot name="image"></slot>
      </div>
      <div class="description">
        <h1 class="text-3xl font-bold pt-10">The Brief</h1>      <!-- Added by me -->
        <slot name="text"></slot>
      </div>
     
    </div>
  </div>
</template>

<style scoped>
  .brief {
    @apply flex flex-col lg:flex-row lg:mt-20;
  }

  .description {
    @apply text-justify lg:pr-5 py-2 leading-relaxed w-full lg:w-1/2 pb-10 lg:ml-5;
  }

  .image {
    @apply lg:w-5/9 lg:-mt-20 grid justify-items-center;
  }
</style>
