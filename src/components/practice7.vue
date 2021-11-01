<template>
  <div class="main_footer">
    <div class="wrap">
      <div class="item">
        <h4>金魚系列 VI - 頁尾資訊區域</h4>
        <ul>
          <li><i class="fas fa-chevron-right"></i>flex-direction 的原理</li>
          <li><i class="fas fa-chevron-right"></i>flex-grow</li>
          <li><i class="fas fa-chevron-right"></i>Google font 使用</li>
          <li><i class="fas fa-chevron-right"></i>font-awesome</li>
        </ul>
      </div>
      <div class="item">
        <h4>公司形象網站必切</h4>
        <ul>
          <li><i class="fas fa-chevron-right"></i>不學起來不行</li>
          <li><i class="fas fa-chevron-right"></i>太常用到了</li>
          <li><i class="fas fa-chevron-right"></i>flex-grow 真好用</li>
          <li><i class="fas fa-chevron-right"></i>快趁機學起來當字典</li>
        </ul>
      </div>
      <div class="item">
        <h4>友站連結</h4>
        <ul>
          <li><i class="fas fa-chevron-right"></i>異業結盟專區</li>
          <li><i class="fas fa-chevron-right"></i>異業都要結盟了</li>
          <li><i class="fas fa-chevron-right"></i>同業還不結盟</li>
          <li><i class="fas fa-chevron-right"></i>團結力量大</li>
        </ul>
      </div>
      <div class="item">
        <h4>訂閱電子報</h4>
        <form>
          <input type="text" placeholder="電子報還沒看就刪掉了" />
          <button class="subsBtn">訂閱</button>
        </form>
      </div>
    </div>
    <div class="copyright">
      <p>copyright &copy; Follow CSScoke Goldfish series by Hsuchihting</p>
    </div>
  </div>
</template>

<style scoped>
.main_footer {
  background: linear-gradient(-270deg, #0d47a1, #03a9f4);
  padding: 100px 0 0 0;
  /* position: fixed; */
  bottom: 0;
  right: 0;
  left: 0;
}
.wrap {
  width: 1200px;
  margin: 0 auto;
  display: flex;
}

.item {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  color: #fff;
  margin-right: 1%;
  margin-left: 1%;
}
.item h4 {
  font-size: 24px;
  border-bottom: 1px dotted #fff;
  font-weight: 700;
  padding-bottom: 10px;
}
.item li {
  font-size: 16px;
  font-weight: 300;
  padding-top: 10px;
  line-height: 1.5;
  cursor: pointer;
}
.item li .fas {
  padding-right: 5px;
  transition: all 0.5s;
}
.item li .fas:hover {
  color: #fbc02d;
}

.item form {
  display: flex;
  margin: auto 0;
}
.item form input {
  width: 80%;
  height: 30px;
  outline: none;
  border: 1px solid #cccccc;
  padding-left: 12px;
}
.item form.subsBtn {
  width: 20%;
  background-color: #fbc02d;
  color: #fff;
  border: none;
  outline: none;
  cursor: pointer;
}
.item form.subsBtn:hover {
  background-color: darken(#fbc02d, 15%);
  transition: all 0.5s;
}

.copyright {
  width: 100%;
  text-align: center;
  color: #ffffff;
  font-weight: 300;
  font-size: 16px;
  background-color: #0a254e;
  padding: 10px 0;
  margin-top: 150px;
}
</style>
