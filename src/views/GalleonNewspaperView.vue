<template>
  <div class="digital-view">
    <div class="title-container">
      <img src="/pinkStar.svg" alt="" />
      <div class="title">Galleon Newspaper</div>
      <img src="/pinkStar.svg" alt="" />
    </div>
    <hr class="line" />
    <div class="rectangle">
      <img src="/ariana.png" alt="" />
    </div>
  </div>
</template>

<style scoped>
.digital-view {
  padding-top: 51px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.title-container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 21px;
  padding-bottom: 15px;
}

.title {
  font-family: Archivo Black;
  font-size: 27px;
  line-height: 29.38px;
  text-align: center;
  color: #ffbb96;
  width: 187px;
}

.line {
  width: 100%;
  border: 3px solid #afcfe8;
  margin-bottom: 40px;
}

.rectangle {
  width: 361px;
  height: 524px;
  border-radius: 20px;
  opacity: 0px;
  border: 3px solid #ffbb96;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
