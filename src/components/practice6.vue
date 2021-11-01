<template>
  <div class="wrap">
    <div class="container">
      <div class="item">
        <div class="pic">
          <img src="https://picsum.photos/400/400?random=25" />
        </div>
        <div class="txt">
          <h2>切版練習五</h2>
          <p>
            dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
          </p>
          <a href="#" class="btn">more</a>
        </div>
      </div>
      <div class="item">
        <div class="pic">
          <img src="https://picsum.photos/400/400?random=22" />
        </div>
        <div class="txt">
          <h2>切版練習五</h2>
          <p>
            dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
          </p>
          <a href="#" class="btn">more</a>
        </div>
      </div>
      <div class="item">
        <div class="pic">
          <img src="https://picsum.photos/400/400?random=20" />
        </div>
        <div class="txt">
          <h2>切版練習五</h2>
          <p>
            dicoge切版練習中/dicoge切版練習中/dicoge切版練習中/dicoge切版練習中
          </p>
          <a href="#" class="btn">more</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrap {
  height: 100vh;
  display: flex;
  align-items: center;
}
.container {
  width: 100%;
  margin: auto;
  display: flex;
}
.item {
  width: 370px;
  margin: 0 15px;
  display: flex;
  
}
.item .pic {
  width: 50%;
}
.item .pic img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  vertical-align: middle;
}
.item .txt {
  width: 50%;
  padding: 20px;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
}

.item .txt h2 {
  font-weight: 900;
}
.item .txt p {
  font-weight: 300;
}
.item .txt .btn {
  line-height: 1.5em;
  border: 1px solid#CCC;
  padding: 0 1em;
  align-self: flex-end;
  border-radius: 200px;
  margin-top: auto;
}
</style>
