<template>
  <div>
    <div class="fixed-bg bg01 text-white">
      <h1>自己紹介</h1>
    </div>
    <div class="scroll-bg my-0 bg02">
      <div class="container">
        <div class="row">
          <div class="col">
            <h3>経歴</h3>
            <ul class="list-group list-group-flush">
              <li class="list-group-item">大阪府立北野高等学校文理学科 卒業</li>
              <li class="list-group-item">京都大学工学部物理工学科機械システム学コース 卒業 </li>
              <li class="list-group-item">京都大学大学院工学研究科機械理工学専攻 在学中</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="fixed-bg bg03 text-white">
      <h1>自分に関係するページ</h1>
    </div>
    <div class="scroll-bg bg04">
      <div class="container">
        <div class="row">
          <div class="col">
            <h3>製作サービス</h3>
            <ul class="list-group list-group-flush">
              <li class="list-group-item"><b-link href="https://www.qweet.net">引用リツイート検索サービス Qweet</b-link></li>
              <li class="list-group-item"><b-link href="">webトランプゲーム(製作中)</b-link></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
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
  background-image: url('~assets/bg03.jpg');
}

.bg04 {
  background-color: #f0d58c;
  padding: 20vh 0;
}

</style>
