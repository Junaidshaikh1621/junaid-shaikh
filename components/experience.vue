<template>
  <div class="text-skin-primary xl:px-70 lg:px-36 md:px-20 px-10 pt-20">
    <h1 class="text-3xl font-bold">Work links</h1>
    <div class="md:grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-y-4 mt-3">
      <div class="Behance">
        <a href="https://www.linkedin.com/in/junaid-shaikh-aa7526202/" target="_blank" rel="nofollow" class="links underlined">Visit LinkedIn</a>
        <a href="https://www.behance.net/junaidshaikh41" target="_blank" rel="nofollow" class="links underlined">Visit Behance</a>
        <a href="https://www.figma.com/@FigmaMale21" target="_blank" rel="nofollow" class="links underlined">Visit Figma</a>
      </div>
      <!-- <div class="history">
        <p class="title">UI/UX Designer</p>
        <p class="present">Zuri Chat <span class="present-tag">Present</span></p>
        <p class="title">Product Designer</p>
        <p class="past">Kid Galaxy PVT Ltd</p>
        <p class="title">Product Designer</p>
        <p class="past">Kratos</p>
        <p class="title">UI/UX Designer</p>
        <p class="past">Zuri I4G</p>
        <p class="title">Creative Director</p>
        <p class="past">Rostrum Couture</p>
      </div> -->
    </div>
  </div>
</template>

<style scoped>
  .links {
    @apply flex my-3;
  }

  .underlined {
    @apply underline;
    text-decoration-color: #CAA519;
    text-decoration-thickness: 2.5px;
    text-underline-offset: 0.2em;
  }

  .underlined:hover {
    text-underline-offset: 0.3em;
  }

  .present {
    @apply text-skin-secondary col-span-2;
  }

  .present-tag {
    @apply text-gray-300 text-xs;
  }

  .resume {
    @apply lg:col-span-2;
  }

  .title {
    @apply col-span-2 md:pl-10 xl:pl-16 2xl:pl-24;
  }

  .past {
    @apply text-gray-300 col-span-2;
  }

  .history {
    @apply grid grid-cols-4 gap-1 my-3 md:col-span-2 lg:col-span-3;
  }
</style>
