<template>
  <div class="header">
        <a href="index.html" class="logo" alt="網站名稱"><img src="https://picsum.photos/50/50"></a>
        <nav class="guidedtour">
          <a href="#">關於我們</a>
          <a href="#">最新消息</a>
          <a href="#">產品</a>
          <a href="#">服務</a>
          <a href="#">聯絡我們</a>
          <a href="#">網站地圖</a>
        </nav>
      </div>

      <!-- Banner -->
      <div class="banner">
        <img src="https://picsum.photos/1200/300">
      </div>

      <!-- path -->
      <div class="path">
        <li><a href="#">關於我們</a></li>
        <li><a href="#">最新消息</a></li>
        <li><a href="#">產品</a></li>
        <li><a href="#">服務</a></li>
        <li><a href="#">聯絡我們</a></li>
        <li><a href="#">網站地圖</a></li>
      </div>

      <div class="about">
        <div class="wrap">
          <h2>關於我們</h2>
        </div>
        <div class="wrap">
          <div class="item">
            <img src="https://picsum.photos/50/50">
            <h3>tittle</h3>
            <p>aaabbbccc</p>
          </div>
          <div class="item">
            <img src="https://picsum.photos/50/50">
            <h3>tittle</h3>
            <p>aaabbbccc</p>
          </div>
          <div class="item">
            <img src="https://picsum.photos/50/50">
            <h3>tittle</h3>
            <p>aaabbbccc</p>
          </div>
        </div>
      </div>
</template>

<style scoped>
.header{
  display: flex;
  padding: 0px 10px;
  background-color: rgb(1, 10, 17);
}
.header .logo{
  display: inline-block;
  padding: 6px 0;
  line-height: 52px;
}

.header nav{
  text-align: right;
  width: 100%;
  font-size: 0;
}

.header nav a{
  font-size: 16px;
  color: blueviolet;
  text-decoration: none;
  display: inline-block;
  line-height: 52px;
  padding: 0px 10px;
}
.header nav a:hover{
  background-color: yellow;
}

.banner img{
  width: 100%;
}
.path{
  display: flex;
}
.path li{
  padding: 6px 8px;
}
.path li a{
  color: grey;
  text-decoration: none;
  font-size: 14px;
}
.path li+li::before{
  content: '/';
  color: aqua;
  position: absolute;
  left: 0;
}

.wrap{
  width:960px;
  margin: auto;
}
.about .wrap{
  display: flex;
}

.about .wrap .item{
  width: 300px;
  margin: 0px 10px;
  text-align: center;
}
</style>
