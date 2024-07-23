<template>
  <div class="xl:px-70 lg:px-36 md:px-20 px-10 text-skin-primary">
    <div class="info">
      <h1 class="text-3xl font-bold">Let's begin!</h1>
      <div class="info-arch">
        <img src="https://i.imgur.com/QQ4EezA.png" alt="junaid-project - harmonify homepage" loading="lazy">
      </div>
    </div>
    <div class="challenges">
      <div class="challenge">
        <div class="challenge-description">
          <h1 class="text-3xl font-bold text-left my-2">Search</h1>
          <p class="challenge-text">The search page for a Spotify clone is designed for a seamless and intuitive user experience. At the top, a prominent search bar allows users to type in queries. As they type, auto-suggestions for songs, artists, albums, playlists, and genres appear. A voice search option is also available for hands-free convenience.</p>
          <p class="challenge-text">Additional features enhance the experience. Filter options let users sort by relevance, popularity, or release date. Search history provides quick access to previous searches. The page is visually appealing with a clean layout and consistent design elements.</p>
        </div>
        <div class="challenge-image">
          <img src="https://i.imgur.com/8EPtqgC.png" alt="junaid-project - harmonify search page" loading="lazy">
        </div>
      </div>
    </div>
    <div class="user-exp">
      <div class="ux">
        <div class="ux-description lg:mr-5">
          <h1 class="text-3xl font-bold my-2">Homepage</h1>
          <p class="user-exp-text">The homepage of Clonify is to enhance the user's music listening experience. User are recommended their favorite artist's music and top music in trend. User can access the music player through the homepage which makes it convinient and easy for them to navigate through the app.</p>
        </div>
        <div class="ux-image">
          <img src="https://i.imgur.com/GPaBcW2.png" alt="junaid-project - harmonify search page" loading="lazy">
          <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509807/projects/barney/case-sbTaxi-App-iPhoneone_amryin.png" alt="barney-case - taxi app iPhone demo" loading="lazy"> -->
          <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509906/projects/barney/case-sbTaxi-App-iPhonetwo_rnk9y6.png" alt="barney-case - taxi app iPhone demo" loading="lazy" class="w-2/3 mb-3 md:-ml-32 -ml-20"> -->
        </div>
      </div>
      <div class="ux">
        <div class="ux-description lg:order-1">
          <h1 class="text-3xl font-bold my-2">Playlist</h1>
          <p class="user-exp-text">Clonify also includes the "Playlist" feature. This feature will allow the user to have direct access to their favorite songs. Users can make different playlists for different events and occassions.</p>
          <p class="user-exp-text">Using the three dots on the right hand side of every song, users can add the song to their playlist. Users can have access to the songs added to their playlist from the "Library" section of the app.</p>
        </div>
        <div class="ux-image">
          <img src="https://i.imgur.com/MHYOJ0V.png" alt="junaid-project - harmonify search page" loading="lazy">
          <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509806/projects/barney/case-sbTaxi-App-iPhonethree_yk5a31.png" alt="barney-case - taxi app iPhone demo" loading="lazy"> -->
          <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509909/projects/barney/case-sbTaxi-App-iPhonefour_sd5lfb.png" alt="barney-case - taxi app iPhone demo" loading="lazy" class="w-5/6 mb-3 md:-ml-28 -ml-16"> -->
        </div>
      </div>
      <div class="ux">
        <div class="ux-description lg:mr-5">
          <h1 class="text-3xl font-bold my-2">Premium</h1>
          <p class="user-exp-text">Users can upgrade to premium which will benefit them to download music and listen offline, listen to high quality music, ad free music, listen with friends in real time and so on. Users can experience the features of premium before buying it through a 1 month trial. Once the trial ends, its up to the user if they want to upgrade to premium.</p>
        </div>
        <div class="ux-image">
          <img src="https://i.imgur.com/mWiYC2L.png" alt="junaid-project - harmonify upgrade page" loading="lazy">
          <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509807/projects/barney/case-sbTaxi-App-iPhoneone_amryin.png" alt="barney-case - taxi app iPhone demo" loading="lazy"> -->
          <!-- <img src="https://res.cloudinary.com/odumz/image/upload/v1666509906/projects/barney/case-sbTaxi-App-iPhonetwo_rnk9y6.png" alt="barney-case - taxi app iPhone demo" loading="lazy" class="w-2/3 mb-3 md:-ml-32 -ml-20"> -->
        </div>
      </div>
    </div>
    <div class="take-away">
      <h1 class="text-3xl font-bold my-2">Key Take-away</h1>
      <p class="take-away-text">Working on this project helped me learn more the role of user experience, typography, color pallette, color contrast, etc. It was my first project and will always be special to me. It may not be perfect but I will always keep it in my portfolio.</p>
    </div>
  </div>
</template>

<style scoped>
.info {
  @apply mb-14;
}

.info-arch {
  @apply grid items-center justify-center py-5;
}

.challenge {
  @apply flex flex-col lg:flex-row gap-3 items-center;
}

.challenge-description {
  @apply text-justify py-2 lg:order-1 leading-relaxed w-full lg:w-1/2 pb-10;
}

.challenge-image {
  @apply lg:w-2/3 grid justify-items-center;
}

.ux {
  @apply flex flex-col lg:flex-row items-center my-12 gap-3;
}

.ux-description {
  @apply text-justify py-2 leading-relaxed w-full lg:w-1/2 pb-10;
}

.ux-image {
  @apply lg:w-2/3 grid grid-cols-1 justify-items-center items-end;
}
/* .ux-image-2 {
  @apply lg:w-1/3 grid grid-cols-1 justify-items-center items-end;
} */

.challenge-text {
  @apply leading-relaxed text-justify mb-3;
}

.take-away {
  @apply flex flex-col py-5 lg:w-2/3 items-center mx-auto lg:pl-10;
}

.take-away-text {
  @apply text-justify leading-relaxed;
}
</style>
