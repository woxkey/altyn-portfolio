<template>
  <div class="digital-view">
    <div class="title-container">
      <img src="/smallStar.svg" alt="" />
      <div class="title">Digital Art</div>
      <img src="/smallStar.svg" alt="" />
    </div>
    <hr class="line" />
    <div class="items">
      <div class="rectangle">
        <img src="/digitalFirst.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/digitalSecond.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/digitalThird.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/digitalFourth.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/digitalFifth.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/digitalSixth.png" alt="" />
      </div>
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
  color: #f9acd6;
}

.line {
  width: 100%;
  border: 3px solid #afcfe8;
  margin-bottom: 40px;
}

.rectangle {
  width: 327px;
  height: 327px;
  border-radius: 20px;
  opacity: 0px;
  border: 3px solid #f9acd6;
  display: flex;
  justify-content: center;
  align-items: center;
}

.items {
  display: flex;
  gap: 34px;
  flex-direction: column;
}
</style>
