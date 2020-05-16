<template>
  <div class="background">
    <div class="container">
      <div>
        <h2 class="title text-white mt-5">
          hongu-ku
        </h2>
        <h2 class="subtitle">
          My GitHub Pages
        </h2>
        <div class="links">
          <a
            href="https://www.qweet.net/"
            target="_blank"
            class="btn btn-success"
          >
            Qweet
          </a>
          <a
            href="https://github.com/hongu-ku"
            target="_blank"
            class="btn btn-secondary"
          >
            GitHub
          </a>
          <!-- <nuxt-link to="profile"><button class='btn btn-primary'>Introduction</button></nuxt-link> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  data() {
    return {
      intro_photo: require('@/assets/intro_photo.jpg')
    }
  }
}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #6af8e5;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.background {
  background-image: url('~assets/intro_photo.jpg');
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}
</style>
