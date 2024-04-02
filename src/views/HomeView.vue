<script setup></script>

<template>
  <div class="home-bg">
    <div class="home-container">
      <div class="home-view">
        <div class="name-container">
          <div class="home-view__name">Altynay Nurmakhanova’s</div>
          <img class="main-star" src="/mainStar.svg" alt="" />
          <img class="secondary-star" src="/secondaryStar.svg" alt="" />
        </div>
        <div class="portfolio">Portfolio:</div>
        <div class="home-view__items">
          <div class="rectangle">
            <RouterLink to="/digital-art">
              <div class="home-view__item">
                <img src="/digitalArtMain.png" alt="" />
                <div class="home-view__itemText">Digital Art</div>
                <div class="digital-bg"></div>
              </div>
            </RouterLink>
          </div>
          <div class="green-rect">
            <RouterLink to="/uiux-design">
              <div class="home-view__item">
                <img src="/uidesignMain.png" alt="" />
                <div class="home-view__itemText">UI/UX Design</div>
                <div class="design-bg"></div>
              </div>
            </RouterLink>
          </div>
          <div class="orange-rect">
            <RouterLink to="/galleon-newspaper">
              <div class="home-view__item">
                <img src="/galleonNewspaperMain.png" alt="" />
                <div class="home-view__itemText">Galleon Newspaper</div>
                <div class="galleon-bg"></div>
              </div>
            </RouterLink>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.home-bg {
  background-color: #fffaf2;
  height: 100vh;
}

.home-container {
  display: flex;
  justify-content: center;
}

.home-view {
  padding-top: 84px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.home-view__items {
  display: flex;
  flex-direction: column;
  gap: 21px;
  align-items: center;
}

.home-view__item {
  position: relative;
  display: inline-block;
}

.home-view__itemText {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-family: Bakbak One;
  font-size: 18.81px;
  line-height: 26.33px;
  color: #f0f9ff;
  z-index: 1;
  text-align: center;
  width: 173px;
}

.home-view__name {
  font-family: 'Black Han Sans';
  font-size: 25.96px;
  font-weight: 400;
  line-height: 32.45px;
  color: #e457a4;
  max-width: 255px;
  text-align: center;
  position: relative;
  z-index: 1;
}

.name-container {
  position: relative;
}

.main-star {
  position: absolute;
  top: -31px;
  left: 0;
}

.secondary-star {
  position: absolute;
  top: -31px;
  left: 126px;
}

.portfolio {
  position: relative;
  font-family: Archivo Black;
  font-size: 27.82px;
  line-height: 30.27px;
  text-align: center;
  color: #afcfe8;
  padding-bottom: 20px;
}

.digital-bg {
  background-color: #f9acd6b2;
  position: absolute;
  width: 285px;
  height: 118px;
  top: 0;
  left: 0;
  border-radius: 18.81px;
}

.design-bg {
  background-color: #cdd3afb2;
  position: absolute;
  width: 284px;
  height: 116.61px;
  top: 0;
  left: 0;
  border-radius: 18.81px;
}

.galleon-bg {
  background-color: #ffbb96b2;
  position: absolute;
  width: 284px;
  height: 116.61px;
  top: 0;
  left: 0;
  border-radius: 18.81px;
}

.rectangle {
  width: 321.61px;
  height: 148px;
  border-radius: 18.81px;
  border: 2.82px solid #f9acd6;
  display: flex;
  justify-content: center;
  align-items: center;
}

.green-rect {
  width: 321.61px;
  height: 148px;
  border-radius: 18.81px;
  border: 2.82px solid #cdd3af;
  display: flex;
  justify-content: center;
  align-items: center;
}

.orange-rect {
  width: 321.61px;
  height: 148px;
  border-radius: 18.81px;
  border: 2.82px solid #ffbb96;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
