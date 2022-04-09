<template>
  <div class="home">
    <div class="home-container">
      <div class="home-container__logo">
        <img src="@/assets/tmp-logo.jpg">
      </div>
      <div class="home-container__title">
        TMP(つくばミュージックプロジェクト)
      </div>
      <div class="home-container__sentence">
        筑波大学学祭に毎年有志でバンドを呼んでいる学生団体です！
      </div>
      <div class="home-container__sns">
        <a href="https://twitter.com/tsukubamusicp" class="home-container__sns-twitter">
          <img src="@/assets/twitter.png">
        </a>
        <a href="https://www.instagram.com/tsukuba_music_p/" class="home-container__sns-insta">
          <img src="@/assets/insta.png">
        </a>
        <a href="https://note.com/tsukuba_music_p/" class="home-container__sns-note">
          <img src="@/assets/note.png">
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.home {
  color: #fff;
  background-color: #000;
  width: 100vw;
  height: 100vh;
  position: relative;
}
.home-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}
.home-container a {
  cursor: pointer;
}
.home-container__logo img {
  width: 480px;
}
.home-container__title {
  margin-top: 20px;
  font-size: 22px;
}
.home-container__sentence {
  margin-top: 32px;
}
.home-container__sns {
  margin-top: 18px;
  display: flex;
  justify-content: center;
}
.home-container__sns img {
  width: 36px;
  border-radius: 4px;
}
.home-container__sns-twitter, .home-container__sns-insta, .home-container__sns-note {
  margin: 24px 32px;
}
@media screen and (max-width: 480px) {
  .home-container {
    text-align: left;
  }
  .home-container__title {
    font-size: 17px;
  }
  .home-container__sentence {
    font-size: 14px;
  }
  .home-container__logo img {
    width: 320px;
  }
}
</style>