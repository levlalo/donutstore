<template>
  <h1>Drink Me</h1>
  <div class="food">
    <div class="drinks">
      <div class="img-wrap">
        <img src="src\assets\1.png" />
      </div>
      <div class="words">
        <h3>Chocolate Ice Tea</h3>
        <p>
          only we offer you to try a chocolate fairytale by drinking our new tea
        </p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
    <div class="drinks">
      <div class="img-wrap">
        <img src="src\assets\2.png" />
      </div>
      <div class="words">
        <h3>Pomegrante Tea</h3>
        <p>Fantastic cool pomegruante tea is waiting for you</p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
    <div class="drinks">
      <div class="img-wrap">
        <img src="src\assets\3.png" />
      </div>
      <div class="words">
        <h3>Sparkling Green Tea</h3>
        <p>Refresh yourself in the summer heart with our green novelty</p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
    <div class="drinks">
      <div class="img-wrap">
        <img src="src\assets\4.png" />
      </div>
      <div class="words">
        <h3>Milky Iced Tea</h3>
        <p>Try the new georgeous taste of milky tea</p>
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
  text-align: center;
  font-size: 45px;
  margin-top: 50px;
}
div.food {
  max-width: 100%;
  margin-left: 150px;
  margin-right: 150px;
  display: flex;
  justify-content: space-between;
  height: 600px;
}
div.drinks {
  width: 240px;
  border-radius: 30px;
  height: 350px;
  background-color: #4cc8ee;
  transition: 0.5s;
}
div.img-wrap {
  height: 350px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.drinks:hover {
  width: 300px;
  height: 530px;
  border-radius: 30px;
  background-color: #7ad7f3;
}
div.words {
  text-align: center;
  overflow-wrap: break-word;
  border-radius: 30px;
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
  font-size: 20px;
  text-align: center;
}
p {
  justify-content: space-between;
  text-align: center;
  font-size: 16px;
  font-weight: 500;
}
.drinks img {
  height: 270px;
  transition: 0.5s;
}
.drinks img:hover {
  height: 310px;
}
</style>