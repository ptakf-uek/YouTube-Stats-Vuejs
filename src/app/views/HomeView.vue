<template>
  <div class="d-flex flex-column justify-content-center align-items-center mt-5">
    <h1>Welcome to YouTubeStats!</h1>
    <h2 class="mt-5 mb-4">Begin your adventure with us and...</h2>

    <div>
      <RouterLink to="/channel/add" class="btn btn-primary fs-4">
        ...add a channel to your tracking list!
      </RouterLink>
    </div>

    <div class="d-flex flex-column justify-content-center align-items-center mt-5">
      <h3 class="mt-3">What is YouTubeStats?</h3>
      <p class="text-center m-0">
        YouTubeStats is a web app that lets you track selected YouTube channels effortlessly.
      </p>
      <p class="text-center m-0">
        Simply add a channel using the Add Channel form, specify which elements you want the app to
        track and visit the Channel List to see all currently tracked channels!
      </p>
    </div>
  </div>
</template>
