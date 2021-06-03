<template>
  <div class="aside">
    <ul class="menu">
      <li><a href="">Top</a></li>
      <li><a href="">Status</a></li>
      <li><a href="">Setting</a></li>
    </ul>
  </div>
</template>
<style scoped>
.aside {
  position: fixed;
  top: 0;
  left: 0;
  text-align: center;
  width: 200px;
  height: 100%;
  background: black;
  color: white;
}

.menu {
  list-style: none;
  padding: 0;
  margin: auto;
  margin-top: 80px;
}
.menu li {
  margin-bottom: 50px;
}
.menu li a {
  color: white;
  text-decoration: none;
  font-size: 25px;
}
</style>
