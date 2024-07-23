<template>
  <div class="xl:px-70 lg:px-36 md:px-20 px-10 text-skin-primary">
    <div class="designs">


      <div class="user-exp">
      <div class="ux">
        <div class="design-description">
          <h1 class="text-3xl font-bold my-2">Design Philosophy</h1>
          <p class="user-exp-text pb-10">The design emphasizes clarity and efficiency, ensuring that users can quickly access and interpret financial data. Clean layouts, intuitive navigation, and visually appealing graphics are central to the user experience, making complex data easy to understand.</p>
          <h1 class="text-3xl font-bold my-2">Objectives</h1>
          <p class="user-exp-text">
            <ul>
            <li>• To provide a clear view of the revenue and sales performance linked to social media campaigns.</li>
            <li>• To identify the most effective social media channels and strategies in driving sales.</li>
            <li>• To offer actionable insights through comprehensive and user-friendly analytics.</li>
          </ul>
        </p>

        </div>
        <div class="design-image">
          <img src="https://i.imgur.com/Z2nDVDo.png" alt="E-circle - key take away" class="rounded pl-5" loading="lazy">
        </div>
      </div>
    </div>



    
      <div class="design">
        <div class="design-description lg:order-1">
          <h1 class="text-3xl font-bold text-left my-2">Design Guide</h1>
          <p class="design-text-lead">This design guide is a tour for the viewers to understand the visual design system that is applied in this project.</p>
          <p class="design-text">In this design guide, I have tried to show the colors that I have used to make the project look visually appealing.</p>
          <p class="design-text">Additionally, the design guide also provides the viewer with information on the icons that have been used in the project.</p>
        </div>
        <div class="design-image ">
          <img src="https://imgur.com/620hINy.png" alt="design guide - E-circle" class="rounded pr-10" loading="lazy">
        </div>
      </div>
    </div>
    <div class="user-exp">
      <div class="ux">
        <div class="design-description">
          <p class="user-exp-text pb-10">All of the designs were created in Figma, which enabled me to work freely because there was already a reference design. Before starting the design, I made all of the components I would need. It was easy to put together.</p>
          <h1 class="text-3xl font-bold my-2">Key Take-away</h1>
          <p class="user-exp-text">I kept the users in front during the design process of the project. Keeping the users in mind can be very helpful while working on the design because empathizing is a key to a great design.</p>
        </div>
        <div class="design-image">
          <img src="https://i.imgur.com/8OoX7vy.jpeg" alt="E-circle - key take away" class="rounded pl-5" loading="lazy">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.design {
  @apply flex flex-col lg:-ml-32 lg:flex-row gap-3 items-center;
}

.design-description {
  @apply text-justify py-2 leading-relaxed w-full lg:w-1/2;
}

.design-image {
  @apply grid relative justify-items-center w-11/12;
}

.ux {
  @apply flex flex-col lg:flex-row lg:-mr-3 items-center my-12 gap-3;
}

.design-text, .design-text-lead {
  @apply leading-relaxed text-justify;
}

.design-text {
  @apply mb-3;
}
</style>
