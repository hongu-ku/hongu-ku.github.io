<template>
  <div>
    準備中
  </div>
</template>

<script>

export default {
  data() {
    return {
      intro_photo: require('@/assets/intro_photo.jpg')
    }
  }
}
</script>

<style scoped>
.container-fluid {
  min-height: 100vh;
}

.fixed-bg {
  justify-content: center;
  align-items: center;
  text-align: center;
  display: flex;

  min-height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}

.scroll-bg {
  background-size: cover;
  background-position: center;
}

.bg01 {
  background-image: url('~assets/bg01.jpg');
}

.bg02 {
  background-color: #f0d58c;
  padding: 20vh 0;
}

.bg03 {
  background-image: url('~assets/bg01.jpg');
}

.bg04 {
  background-image: url('~assets/bg01.jpg');
}

</style>
