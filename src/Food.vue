<template>
  <h1>Eat Me</h1>
  <div class="food">
    <div class="donut">
      <div class="img-wrap">
        <img src="./assets/chok.png" />
      </div>
      <div class="words">
        <h3>Chocolate Wheal</h3>
        <p>
          At the base is yeast dough. The filling is chocolate paste, covered
          with delicate chocolste glaze
        </p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
    <div class="donut">
      <div class="img-wrap">
        <img src="./assets/pink.png" />
      </div>
      <div class="words">
        <h3>Strawbery Miracle</h3>
        <p>
          At the base is yeast dough with the addition of ingredients that give
          the special taste
        </p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
    <div class="donut">
      <div class="img-wrap">
        <img src="./assets/milk.png" />
      </div>
      <div class="words">
        <h3>Vanilla Joy</h3>
        <p>
          Delicious donut without filling in sugar glaze with white chocolate in
          vanilla flavor
        </p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  color: #007e91;
  margin-top: 0px;
  text-align: center;
  font-size: 45px;
}
div.food {
  max-width: 100%;
  margin-left: 150px;
  margin-right: 150px;
  display: flex;
  justify-content: space-between;
}
div.donut {
  width: 300px;
}
div.img-wrap {
  height: 350px;
  display: flex;
  justify-content: center;
  align-items: center;
}
div.img-wrap:hover + .words h3 {
  color: #ff5079;
}
div.words {
  text-align: center;
  overflow-wrap: break-word;
}
div.order {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.order a {
  border-radius: 20px;
  color: white;
  text-decoration: none;
  text-align: center;
  font-size: 24px;
  padding: 5px 13px;
  background-color: #024abd;
}
.order p {
  margin: 0%;
  font-size: 35px;
  font-weight: 800;
  color: #21af04;
}
h3 {
  margin-top: 0px;
  margin-bottom: 0px;
  font-weight: 800;
  font-size: 25px;
  text-align: center;
  transition: 0.5s;
}
p {
  text-align: center;
  font-size: 16px;
  font-weight: 600;
}
.donut img {
  height: 330px;
  transition: 0.8s;
}
.donut img:hover {
  height: 360px;
}
</style>
