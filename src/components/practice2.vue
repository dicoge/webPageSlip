<template>
  <div class="banner">
       <div class="container">
          <div class="banner-txt">
            <h1>
              封面頁練習
              <small>
                dicoge練習中
              </small>
            </h1>
            <h2>
              圖文滿版區塊
            </h2>
            <p>
              123123123123<br>123123123
            </p>
          </div>
       </div>
       </div>
</template>

<style scoped>
.banner{
width: 100%;
height: 100vh;
background-color: rebeccapurple;
background: linear-gradient(115deg,#7bf 50%,transparent 50%)center center/100% 100%,
url("https://picsum.photos/300/200")right center /auto 100%;
}

.container{
  height: 100%;
  max-width: 1440px;
  width: 1200px;
  margin: auto;
}

.banner-txt{
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}

.banner-txt h1{
  font-size: 80px;
  border-bottom: 1px solid brown;
}

.banner-txt h1 small{
  display: block;
  font-size: 54px;
}

.banner-txt h2{
  font-size: 50px;
}

.banner-txt p{
  font-size: 30px;
}
</style>
