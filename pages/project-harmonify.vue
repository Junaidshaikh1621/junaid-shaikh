<template>
  <div class="fontface bg-skin-secondary-accent">
    <ProjectTopbar class="pt-14 text-white" />
    <ProjectSummary class="mt-7 mb-16">
      <template #title>
        <h1 class="text-5xl font-medium mb-6">Harmonify</h1>
      </template>
    </ProjectSummary>
    <div class="bg-white">
      <brief2 class="py-10">
        <template #text>
          <p>Harmonify is a comprehensive music streaming application designed to let users discover, play, and share music seamlessly, featuring an extensive library of songs, albums, and artists, personalized recommendations based on individual listening habits, user-created playlists, robust search functionality, and social features that enable following friends and sharing musical experiences. </p>
        </template>
        <template #image>
          <!-- <img src="https://i.imgur.com/qlfmlt6.png" alt="case taxi app - brief" loading="lazy"> -->
        </template>
      </brief2>
      <taxi class="pt-10 pb-32" />
      <hoverchat class="hidden md:flex sticky inset-y-1/4 inset-x-10/12 xl:inset-x-18/21" />
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Harmonify - Junaid',
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
