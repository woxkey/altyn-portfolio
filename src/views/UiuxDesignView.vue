<template>
  <div class="design-view">
    <div class="title-container">
      <img src="/orangeStar.svg" alt="" />
      <div class="title">UI/UX Design</div>
      <img src="/orangeStar.svg" alt="" />
    </div>
    <hr class="line" />
    <div class="items">
      <div class="rectangle">
        <img src="/design1.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/design2.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/design3.png" alt="" />
      </div>
      <div class="rectangle">
        <img src="/design4.png" alt="" />
      </div>
      <div class="rectangle h-372">
        <img src="/design5.png" alt="" />
      </div>
      <div class="rectangle h-310">
        <img src="/design6.png" alt="" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.design-view {
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
  color: #cdd3af;
}

.line {
  width: 100%;
  border: 3px solid #afcfe8;
  margin-bottom: 40px;
}

.rectangle {
  width: 356px;
  height: 275px;
  border-radius: 20px;
  opacity: 0px;
  border: 3px solid #cdd3af;
  display: flex;
  justify-content: center;
  align-items: center;
}

.items {
  display: flex;
  gap: 34px;
  flex-direction: column;
}

.h-372 {
  height: 372px;
}

.h-310 {
  height: 310px;
}
</style>
