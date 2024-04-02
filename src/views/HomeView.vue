<script setup></script>

<template>
  <div class="home-bg">
    <div class="home-container">
      <div class="home-view">
        <div class="home-view__name">Altynay Nurmakhanova’s</div>
        <div>Portfolio:</div>
        <div class="home-view__items">
          <RouterLink to="/digital-art">
            <div class="home-view__item">
              <img src="/digitalArtMain.png" alt="" />
              <div class="home-view__itemText">Digital Art</div>
            </div>
          </RouterLink>
          <RouterLink to="/uiux-design">
            <div class="home-view__item">
              <img src="/uidesignMain.png" alt="" />
              <div class="home-view__itemText">UI/UX Design</div>
            </div>
          </RouterLink>
          <RouterLink to="/galleon-newspaper">
            <div class="home-view__item">
              <img src="/galleonNewspaperMain.png" alt="" />
              <div class="home-view__itemText">Galleon Newspaper</div>
            </div>
          </RouterLink>
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
  padding-top: 50px;
}

.home-view__items {
  display: flex;
  flex-direction: column;
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
}

.home-view__name {
  font-family: 'Black Han Sans';
  font-size: 25.96px;
  font-weight: 400;
  line-height: 32.45px;
  color: #e457a4;
  max-width: 255px;
  text-align: center;
}
</style>
