<template>
  <div class="intro">
    <div class="words">
      <h1>Promotion!</h1>
      <p>
        Only in Dounuts Go during the winter, if your order is more than 20$,
        the delyvery is free. And remember that every 1$, from your order, goes
        to the low-income familes!
      </p>
      <div class="order"><a href="#">Order Online</a></div>
    </div>
    <div class="donuts">
      <img src="./assets/donuts.png" />
    </div>
  </div>
  <svg viewBox="0 0 1440 70" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M0 67.4047L1440 67.4047V7.62939e-06H1380C1320 7.62939e-06 1200 7.62939e-06 1080 7.62939e-06C960 7.62939e-06 840 7.62939e-06 720 7.62939e-06C600 7.62939e-06 480 7.62939e-06 360 7.62939e-06C240 7.62939e-06 120 7.62939e-06 60 7.62939e-06H0V67.4047Z"
      fill="#FF5079"
    />
    <path
      d="M0 0L60 11.6548C120 21.9548 240 48.1851 360 42.4851C480 37.1851 600.181 11.6548 720.181 11.6548C840.181 11.6548 955.823 35.6094 1075.82 40.9094C1195.82 46.6094 1311 26.1375 1371 15.8375L1440 0V63.4915H0V0Z"
      fill="#6CD2DE"
    />
    <path
      d="M0 0L60 13.7C120 31 240 58 350 53.3C480 42 600 24.0563 720 21.0563C840 24.0563 960 45 1080 52.3C1200 56 1320 36 1380 16.7L1440 0V69.5583H0V0Z"
      fill="white"
    />
  </svg>
</template>

<style scoped>
div.intro {
  display: flex;
  justify-content: start;
  align-items: normal;
  background-color: #ff5079;
}
div.words {
  display: flow-root;
  margin: 80px 250px 0 139px;
  font-size: 20px;
  color: white;
  font-weight: 300;
}
div.order {
  margin-top: 50px;
}
a {
  border-radius: 20px;
  color: white;
  text-decoration: none;
  text-align: center;
  font-size: 24px;
  padding: 6px 24px;
  background-color: rgb(102, 26, 241);
  transition: 0.1s linear;
}
a:hover {
  background-color: rgb(106, 25, 255);
}
div.donuts {
  margin-right: 200px;
}
img {
  height: 400px;
}
</style>
