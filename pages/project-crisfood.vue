<template>
  <div class="fontface bg-skin-tertiary-accent">
    <ProjectTopbar class="pt-14 text-white" />
    <ProjectSummary class="mt-7 mb-16">
      <template #title>
        <h1 class="text-5xl font-medium mb-6">Crisfood</h1>
      </template>
    </ProjectSummary>
    <div class="bg-white">
      <brief class="pt-10">
        <template #text>
          <p>Crisfood is a cutting-edge online food ordering app designed to connect users with their favorite local restaurants effortlessly. Combining intuitive design with powerful features, Crisfood aims to revolutionize the food ordering experience by offering a seamless and personalized service for both customers and restaurant partners.</p>
          <p class="mt-2">The client desired a simple, slick, and memorable identity that reflected their ideals and could be scaled adequately for marketing collateral and clients.</p>
        </template>
        <template #image>
          <img src="https://i.imgur.com/3BRW9HA.jpeg" alt="app Crisfood - brief" loading="lazy" class="my-auto">
        </template>
      </brief>
      <chat class="pb-32" />
      <chat-footer />
      <hoverchat class="hidden md:flex sticky inset-y-1/4 inset-x-10/12 xl:inset-x-18/21" />
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Crisfood - Junaid',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Good design, in my opinion, should be usable, straightforward, and appealing, and should be the outcome of a thorough understanding of the target user.'
      }
    ],
  }
}
</script>

<style scoped>
  .fontface {
    font-family: Rubik, sans-serif;
  }

</style>
