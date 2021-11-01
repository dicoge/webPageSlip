<template>
  <div class="wrap">
    <div class="item">
      <img src="https://picsum.photos/500/400?random=7" />
      <div class="txt">
        <h2>切版練習三</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>
    <div class="item">
      <img src="https://picsum.photos/500/400?random=8" />
      <div class="txt">
        <h2>切版練習三</h2>
        <p>
          dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
        </p>
      </div>
    </div>
    <div class="item">
      <img src="https://picsum.photos/500/400?random=9" />
      <div class="txt">
        <h2>切版練習三</h2>
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
  display: flex;
  margin: auto;
}

.item {
  width: 368;
  margin: 15px;
  text-align: center;
  border: 1px solid gray;
  transform: translateY(0px);
  transition: 0.5s;
}

.item img {
  width: 100%;
  vertical-align: middle;
}

.item .txt {
  padding: 20px;
  position: relative;
}
.item .txt::before {
  content: ' ';
  position: absolute;
  width: 0;
  height: 0;
  left: 0;
  top: 0;
  border-top: 50px solid transparent;
  border-left: 184px solid #fff;
  border-right: 184px solid #fff;
  transform: translateY(-100%);
}
.item:hover{
  transform: translateY(-50px);
  background-image: linear-gradient(0deg,#FF0,#FF9);
}

.item:hover .txt::before{
    border-left: 184px solid #FEB85D;
  border-right: 184px solid #FEB85D;
}

.item:hover h2 {
color: #F00;
border-color: #0F0;
}
.item:hover p {
color: #F00;
}
.item h2 {
  border-bottom: 1px solid #888;
  padding-bottom: 0.3em;
  margin-bottom: 0.4em;
  font-weight: 900;
  transition: 0.25s;
}
.item p {
  line-height: 1.5;
  font-weight: 300;
  transition: 0.25s;
}
</style>
