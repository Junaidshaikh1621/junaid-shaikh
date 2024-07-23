<template>
  <div class="fontface bg-skin-tertiary">
    <ProjectTopbar class="pt-14 text-white" />
    <ProjectSummary class="mt-7 mb-16">
      <template #title>
        <h1 class="text-5xl font-medium mb-6">E-circle</h1>
      </template>
      <template #default>
        <span>February, 2024</span>
      </template>
    </ProjectSummary>
    <div class="bg-white">
      <brief class="py-10">
        <template #text>
          <p class="pr-12">The "Dashboard for Social Media Analytics" project is designed to help businesses track and analyze the revenue and sales generated through social media channels. This tool provides valuable insights into the financial impact of social media activities, allowing companies to make informed strategic decisions.

</p>
          <p class="mt-2 pr-12">The dashboard also depicts three different charts.<ul>  <li>1. Revenue: This chart allows the team to determine whether they occured a loss or made profit.</li> <li>2. Expenses: On the other hand, the team can see how much they spent during the time.</li><li>3. Sales: This chart is useful to determine the products/services which are giving profits and which aren't.</li></ul> </p>
        </template>
        <template #image>
          <img src="https://i.imgur.com/ro4nPXJ.jpeg" alt="Dashboard - brief" loading="lazy" class="mt-20">
        </template>
      </brief>
      <krypto class="pt-10" />
      <hoverchat class="hidden md:flex sticky inset-y-1/4 inset-x-10/12 xl:inset-x-18/21" />
      <krypto-footer />
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'E-circle - Junaid',
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
