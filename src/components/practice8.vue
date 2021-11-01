<template>
  <div class="header">
    <div class="container">
      <a href="#" class="logo">
        <i class="fab fa-spotify fa-3x"></i>
        <span>Spotify</span>
      </a>

      <nav class="navbar">
        <a href="#" class="item">金魚系列 VII</a>
        <a href="#" class="item">每個網站都有的導覽列</a>
        <a href="#" class="item">選項一定要有互動</a>
        <a href="#" class="item">這個不會不行</a>
      </nav>
      <form class="navSearch">
        <input type="search" placeholder="找不到東西的搜尋列" />
        <button><i class="fas fa-search"></i></button>
      </form>
    </div>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
  color: #26ff93;
  font-weight: 300;
}
.header {
  background-image: linear-gradient(90deg, #333, #555);
}
.header .container {
  display: flex;
  max-width: 1200px;
  margin: 0 auto;
}

.header .container.logo {
  margin-right: 1em;
  display: flex;
  align-items: center;
}
.header .container.logo .fa-spotify {
  padding-right: 0.5em;
  color: #26ff93;
}
.header .container.logo span {
  font-size: 26px;
  font-weight: 500;
}
.navbar {
  display: flex;
  align-items: center;
  margin: auto;
}
.navbar .item {
  flex-grow: 1;
  padding: 20px;
  border-bottom: 5px solid transparent;
  transition: 0.3s;
}
.navbar .item:hover {
  border-bottom: 5px solid #26ff93;
}

.navSearch {
  display: flex;
  align-items: center;
  margin-left: auto;
}
.navSearch input,
button {
  border: none;
  outline: none;
  height: 30px;
  background-color: #ffffff;
}
.navSearch input {
  padding-left: 12px;
  width: 80%;
  border-radius: 100px 0 0 100px;
}
.navSearch button {
  width: 20%;
  border-radius: 0 100px 100px 0;
  cursor: pointer;
}
.navSearch .fa-search {
  color: #555555;
}
.navSearch .fa-search:hover {
  color: #26ff93;
  transition: all 0.3s;
}
</style>
