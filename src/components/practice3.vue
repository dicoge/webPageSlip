<template>
  <div class="wrap">
    <div class="item">
      <img src="https://picsum.photos/500/400?random=3" />
      <div class="txt">
        <h2>切版練習二</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>

    <div class="item">
      <img src="https://picsum.photos/500/400?random=4" />
      <div class="txt">
        <h2>切版練習二</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>

    <div class="item">
      <img src="https://picsum.photos/500/400?random=5" />
      <div class="txt">
        <h2>切版練習二</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>

    <div class="item">
      <img src="https://picsum.photos/500/400?random=6" />
      <div class="txt">
        <h2>切版練習二</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrap {
  width: 100%;
  display: flex;
}

.item {
  width: 25%;
  position: relative; /* 相對定位 */
}

.item img {
  width: 100%;
  vertical-align: middle;
}

.item .txt {
  position: absolute; /* 絕對定位 */
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 20px;
  background-color: rgba(0, 0, 0, 0.6);
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-direction: column;
  opacity: 0; /* 透明度 */
  transition: opacity 0.5s;
}
.item:hover .txt {
  opacity: 1; /* 透明度 */
}
.item h2 {
  font-size: 36px;
  color: lightskyblue;
}

.item h2:after {
  content: " ";
  display: block;
  width: 0%;
  height: 2px;
  margin: 10px 0;
  background-color: #ff0;
  transition: width 0.3s 0.3s;
}
.item:hover h2:after {
  width: 100%;
}
.item p {
  font-size: 18px;
  color: palevioletred;
}
</style>
