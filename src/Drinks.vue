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
        <img src="src\assets\2.png" />
      </div>
      <div class="words">
        <h3>Pomegrante Tea</h3>
        <p>Fantastic cool pomegruante tea is waiting for you;ololololololol</p>
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
        <p>Try the new georgeous taste of milky tea lololololollolololollol</p>
        <div class="order">
          <a href="#">Order</a>
          <p class="dol">10 $</p>
        </div>
      </div>
    </div>
  </div>
  <svg viewBox="0 0 1440 70" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M0 58.3342L1440 58.3342V2.42773e-05H1380C1320 2.42773e-05 1200 2.42773e-05 1080 2.42773e-05C960 2.42773e-05 840 2.42773e-05 720 2.42773e-05C600 2.42773e-05 480 2.42773e-05 360 2.42773e-05C240 2.42773e-05 120 2.42773e-05 60 2.42773e-05H0V58.3342Z"
      fill="white"
    />
    <path
      d="M0 0L60 11.6548C120 21.9548 240 48.1851 360 42.4851C480 37.1851 600.181 11.6548 720.181 11.6548C840.181 11.6548 955.823 35.6094 1075.82 40.9094C1195.82 46.6094 1311 26.1375 1371 15.8375L1440 0V63.4915H0V0Z"
      fill="#6CD2DE"
    />
    <path
      d="M0 0L60.1843 13.787C120.369 31.1969 240.737 58.3683 351.075 53.6385C481.475 42.2667 601.843 24.2091 722.212 21.19C842.581 24.2091 962.949 45.2858 1083.32 52.6321C1203.69 56.3556 1324.06 36.2286 1384.24 16.8061L1444.42 0V70H0V0Z"
      fill="#FF5079"
    />
  </svg>
</template>



<style scoped>
h1 {
  color: #007e91;
  text-align: center;
  font-size: 45px;
  margin-top: 50px;
  margin-bottom: 60px;
}
div.food {
  max-width: 100%;
  margin-left: 150px;
  margin-right: 150px;
  display: flex;
  justify-content: space-between;
  height: 530px;
}
div.drinks {
  width: 250px;
}
div.img-wrap {
  height: 280px;
  display: flex;
  justify-content: center;
  align-items: center;
}
div.img-wrap:hover + div.words {
  height: 180px;
  border-radius: 30px;
  background-color: #7ad7f3;
}
div.img-wrap:hover + div.words h3 {
  color: #ff5079;
}
div.words {
  text-align: center;
  overflow-wrap: break-word;
  margin-top: -200px;
  padding-top: 245px;
  padding-left: 5px;
  padding-right: 5px;
  height: 0px;
  border-radius: 30px;
  background-color: #4cc8ee;
  transition: 0.6s;
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
  margin-top: 10px;
  margin-bottom: 0px;
  font-weight: 800;
  font-size: 20px;
  text-align: center;
  transition: 0.5s;
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