<template>
  <div class="xl:px-70 lg:px-36 md:px-20 px-10 text-skin-primary">
    <h1 class="text-3xl font-bold">Expertise</h1>
    <div class="grid sm:grid-cols-3 gap-4">
      <div class="links">
        <ul class="my-3">
          <li class="mb-3">
            <a href="https://www.behance.net/junaidshaikh41" target="_blank" rel="nofollow" class="underlined">Behance</a>
          </li>
          <!-- <li class="my-3">
            <a href="https://dribbble.com/baneyzinsane" target="_blank" rel="nofollow" class="underlined">Dribble</a>
          </li>
          <li class="my-3">
            <a href="https://www.instagram.com/barneyzinsane/" target="_blank" rel="nofollow" class="underlined">Instagram</a>
          </li> -->
        </ul>
      </div>
      <div class="skills">
        <div class="my-3">
          <h2 class="title">UX Design</h2>
          <ul>
            <li>
              <p class="text-lg">User research</p>
            </li>
            <li>
              <p class="text-lg">Crafting user stories</p>
              <li>
              <p class="text-lg">Usability testing</p>
            </li>
            </li>
            <li>
              <p class="text-lg">Wireframing</p>
            </li>
            <li>
              <p class="text-lg">Lo-fi & Hi-fi prototyping</p>
            </li>
          </ul>
        </div>
        <div class="my-3">
          <h2 class="title">UI Design</h2>
          <ul>
            <li>
              <p class="text-lg">Visual Design</p>
            </li>
            <li>
              <p class="text-lg">Responsive Web Design</p>
            </li>
            <li>
              <p class="text-lg">Prototyping</p>
            </li>
            <li>
              <p class="text-lg">Interaction Design</p>
            </li>
            <li>
              <p class="text-lg">User-centered Design</p>
            </li>
            
          </ul>
        </div>
        <!-- <div class="my-3">
          <h2 class="title">Process</h2>
          <ul>
            <li>
              <p class="text-lg">Understand</p>
            </li>
            <li>
              <p class="text-lg">Contextualize</p>
            </li>
            <li>
              <p class="text-lg">Explore</p>
            </li>
            <li>
              <p class="text-lg">Validate</p>
            </li>
            <li>
              <p class="text-lg">Build</p>
            </li>
          </ul>
        </div> -->
        <div class="my-3">
          <h2 class="title">Tools</h2>
          <ul>
            <li>
              <p class="text-lg">Figma</p>
            </li>
            <li>
              <p class="text-lg">AdobeXD</p>
            </li>
            <li>
              <p class="text-lg">Figjam</p>
            </li>
            <li>
              <p class="text-lg">Dora 3D Web</p>
            </li>
            <li>
              <p class="text-lg">Adobe Photoshop</p>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .links {
    @apply grid;
  }

  .skills {
    @apply grid md:grid-cols-2 sm:col-span-2;
  }

  .title {
    @apply text-2xl font-bold mb-2;
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
</style>
