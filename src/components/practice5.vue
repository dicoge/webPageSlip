<template>
  <div class="wrap">
    <div class="item">
      <div class="pic">
        <img src="https://picsum.photos/600/350?random=10" />
      </div>
      <div class="txt">
        <h2>切版練習四</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>
    <div class="item">
      <div class="txt">
        <h2>切版練習四</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
      <div class="pic">
        <img src="https://picsum.photos/600/350?random=11" />
      </div>
    </div>
    <div class="item">
      <div class="pic">
        <img src="https://picsum.photos/600/350?random=12" />
      </div>
      <div class="txt">
        <h2>切版練習四</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrap {
  width: 1200px;
  margin: auto;
}

.item {
  display: flex;
  align-items: center;
  margin-bottom: 70px;

}
.item .pic {
  width: 55%;
}
.item .txt {
  width: 55%;
  flex-shrink: 0;
  background-color: #fa8;
  padding: 50px 30px;
  box-sizing: border-box;
  z-index: 1;
}
.item .pix img {
  width: 100%;
  vertical-align: middle;
}
.item h2{
font-weight: 900;
}
.item p{
font-weight: 300;
}
.item > :first-child {
  margin-right: -10%;
}
.item:nth-child(1) .txt {
  background-color:rgba(240,174, 193, 0.8)
}
.item:nth-child(2) .txt {
  background-color: rgba(42,253, 208, 0.8);
}
.item:nth-child(3) .txt {
  background-color: rgba(254,201, 121, 0.8);
}
.item:nth-child(4) .txt {
  background-color: rgba(149,219, 214, 0.8);
}
</style>
