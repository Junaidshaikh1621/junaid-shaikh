<template>
  <div class="topbar">
    <div class="left-side">
      <div class="profile photo">
        <NuxtLink to="/" class="flex items-center uppercase mb-4 text-sm">
          <img src="https://i.imgur.com/TKgUMkW.jpeg" alt="photo" class="w-16 rounded-full">
        </NuxtLink>
      </div>
      <div class="name">
        <p>Junaid</p>
        <p class="-mt-2">Shaikh</p>
      </div>
    </div>
    <!-- <div class="right-side">
      <NuxtLink to="/about" class="hover:opacity-80">
        About me
      </NuxtLink>
    </div> -->
  </div>
</template>

<style scoped>
  .topbar {
    @apply md:flex text-skin-primary justify-between items-center xl:mx-70 lg:mx-36 md:mx-20 mx-10 bg-gray-100 overflow-hidden;
  }

  .left-side {
    @apply flex items-center uppercase;
  }

  .right-side {
    @apply uppercase;
  }

  .logo {
    @apply mr-6;
  }

  .name {
    @apply uppercase -mt-3;
  }
</style>
