<template>
  <div class="text-skin-primary lg:px-70 md:px-20 px-10 py-10 overflow-hidden">
    <h1 class="text-3xl font-bold">Projects</h1>
    <div class="case-study">
      <div v-for="casebrief in cases" :key="casebrief.image" >
        <div class="case hover:shadow-lg rounded px-3 pb-3">
          <CaseStudy class="">
            <template #image>
              <img :src="casebrief.image" :alt="casebrief.description" loading="lazy" class="w-96">
            </template>
            <template #title>
              <nuxt-link :to="{ path: casebrief.link }">
                {{ casebrief.title }}
              </nuxt-link>
            </template>
            <template #description>
              {{ casebrief.description }}
            </template>
          </CaseStudy>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    scrollToTop: true,
    data() {
      return {
        cases: [
          {
            image: 'https://i.imgur.com/2sbGGxx.png',
            title: 'Harmonify',
            link: 'project-harmonify',
            description: 'Creating an Unforgettable Music Experience'
          },
          {
            image: 'https://i.imgur.com/jcFnCcO.jpeg',
            title: 'Analytical Dashboard',
            link: 'project-analytical-dashboard',
            description: 'Dashboard for Social Media Analytics'
          },
          {
            image: 'https://i.imgur.com/XgAkhrx.jpeg',
            title: 'Crisfood',
            link: 'project-crisfood',
            description: 'Your Desired Destination to Order Food Online'
          },
          {
            image: 'https://i.imgur.com/VSsHpHi.jpeg',
            title: 'Coming soon...',
            description: 'Healtcare Practitioner Project Coming Soon...'
          }
        ]
      }
    }
  }
</script>

<style scoped>
  .case-study {
    @apply grid lg:grid-cols-2 my-12 justify-center;
  }

  .case {
    @apply md:my-1 my-2 lg:-mx-1 grid justify-items-center;
  }
</style>
