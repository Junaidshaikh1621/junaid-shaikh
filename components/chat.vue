<template>
  <div class="xl:px-70 lg:px-36 md:px-20 px-10 text-skin-primary">
    <div class="user-exp">
      <div class="design">
        <div class="design-description">
          <h1 class="text-3xl font-bold my-2">Homepage</h1>
          <p>The homepage of the Crisfood app is designed to be the central hub where users can easily access all the essential features of the app. It allows users to find their desired restaurant to order food from.</p>
          <p>Users can also access to the offers from the homepage itslef as the app focuses on online food ordering and provides users with great offers.</p>
        </div>
        <div class="design-image">
          <img src="https://i.imgur.com/5md9ai0.jpeg" alt="Crisfood Homepage" class="" loading="lazy">
          <!-- <p class="text-gray-400 py-3 text-sm">Creative explorations and early drafts of Notice Board</p> -->
        </div>
      </div>
      <div class="design">
        <div class="design-image">
          <img src="https://i.imgur.com/myQ2ZH0.jpeg" alt="Crisfood Cart" class="" loading="lazy">
          <!-- <p class="text-gray-400 py-3 text-sm">Creative explorations and early drafts of Notice Board</p> -->
        </div>
        <div class="design-description">
          <h1 class="text-3xl font-bold my-2">Cart</h1>
          <p>The Cart page on Crisfood is designed to offer users a seamless and efficient checkout experience. Upon adding items to the cart, users are directed to a clean, well-organized page where they can review their selections. Each item is displayed with a thumbnail image, name, customization options, price, and quantity controls. Users can easily modify their order by adjusting quantities or removing items with a simple tap.</p>
          <p>A summary section at the bottom provides a clear breakdown of costs, including item subtotals, taxes, delivery fees, and any applicable discounts or promotions. A prominently displayed total amount ensures users are aware of their final cost before proceeding.</p>
        </div>
      </div>
    </div>
    <div class="take-away">
      <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509813/projects/barney/case-ZuriChat-logo_bomgnz.png" alt="ZuriChat logo" class="md:w-3/7 w-5/7" loading="lazy"> -->
      <!-- <p class="take-away-text md:pl-4">Final Logo Design</p> -->
    </div>
    <div class="pt-10">
      <div class="design">
        <div class="design-image">
          <img src="https://i.imgur.com/Z897ZWu.jpeg" alt="ZuriChat original view" class="transform scale-105" loading="lazy">
          <p class="text-gray-400 py-3 text-sm">Homepage Wireframe</p>
        </div>
        <div class="design-image">
          <img src="https://i.imgur.com/Gf0rf0M.jpeg" alt="ZuriChat darkmode" loading="lazy">
          <p class="text-gray-400 py-3 text-sm">Cart Wireframe</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.design {
  @apply flex flex-col lg:flex-row items-center mt-10 mb-12 gap-3;
}

.design-description {
  @apply text-justify py-2 leading-relaxed w-full lg:w-1/2;
}

.design-image {
  @apply lg:w-1/2 grid justify-items-center;
}

.take-away {
  @apply flex flex-col items-center;
}

.take-away-text {
  @apply text-justify leading-relaxed -mt-6 md:tracking-widest sm:tracking-wider text-gray-500;
}
</style>
