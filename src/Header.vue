<template>
  <header class="header">
    <div class="container">
      <div class="inhead">
        <img alt="Donut logo" src="src\assets\logoDonut.png" />
        <nav>
          <a class="nav_to" href="#">Eat Me</a>
          <a class="nav_to" href="#">Drink Me</a>
          <a class="nav_to" href="#">Delivery</a>
          <a class="nav_to" href="#">About</a>
          <a class="nav_to" href="#">Contacts</a>
        </nav>
      </div>
    </div>
  </header>
</template>

<style scoped>
header {
  background-color: #ff5079;
}
div.container {
  width: 100%;
  max-width: 1350px;
  margin: 0 auto;
}
div.inhead {
  display: flex;
  align-items: center;
  padding-top: 30px;
}
img {
  height: 150px;
  margin-left: 80px;
}
nav {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  font-size: 26px;
  font-weight: 600;
  margin-right: 80px;
}
a {
  border-radius: 15px;
  color: #ffffff;
  text-decoration: none;
  text-align: center;
  padding: 6px 18px;
  opacity: 0.8;
  transition: 0.1s linear;
}

a.nav_to:hover {
  background-color: #ff688b;
  opacity: 0.9;
  font: bold;
}
div.upper {
  height: 550px;
  background-color: #ff84a1;
}
</style>