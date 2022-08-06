<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<style></style>
<template>
  <header>
    <nav>
      <div class="nav-wrapper">
        <img alt="company logo" class="logo" src="@/assets/LogoSrc.svg" />
        <div class="btn-container">
          <a href="/login">Login</a>
          <button class="btn">Register</button>
        </div>
      </div>
    </nav>

    <!-- <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div> -->
  </header>
  <div class="hero-container">
    <div class="left">
      <div class="content-container">
        <h1>AnyTime, anywhere Learn on your schedule from any device</h1>
        <h4>
          We Believe everyone has the capcity to be creative
          <span>Course Pro</span> is a place where people develop their own
          potential
        </h4>
        <button class="btn black">Let's Get Start</button>
      </div>
    </div>
    <div class="right">
      <img src="@/assets/hero-image.jpg" />
    </div>
  </div>
  <div class="stats-wrapper">
    <div class="stats-content">
      <h3>Total Students</h3>
      <h1>5140</h1>
    </div>
    <div class="stats-content">
      <h3>Partners</h3>
      <h1>4123</h1>
    </div>
    <div class="stats-content">
      <h3>Affiliate Distribution</h3>
      <h1>4.18 Lac</h1>
    </div>
  </div>

  <div class="courses-container">
    <p>Courses</p>
    <h1>Our Most Popular Courses</h1>
    <div class="courses-wrapper">
      <div class="card">
        <img class="card-img" src="@/assets/card-img1.jpg" />
        <div class="card-content-wrapper">
          <h3>Ultimate Business Intelligence Analyst A to Z Course 2021</h3>
          <p><span>46,995</span> Student</p>
          <div class="timeline">
            <div>
              <img class="icon-img" src="@/assets/schedule.svg" /> 11 hr 20 mins
            </div>
            <div>
              <img class="icon-img" src="@/assets/date.svg" />
              44 Lectures
            </div>
          </div>
          <div class="user-panel">
            <div class="username">
              <img class="user-img" src="@/assets/user-img1.jpg" />
              <span>Albert Hitler</span>
            </div>
            <div class="price">₹2000<span>₹2000</span></div>
          </div>
        </div>
      </div>
      <div class="card">
        <img class="card-img" src="@/assets/card-img2.jpg" />
        <div class="card-content-wrapper">
          <h3>Adobe Photoshop Training: From Beginner to Pro</h3>
          <p><span>6,995</span> Student</p>
          <div class="timeline">
            <div>
              <img class="icon-img" src="@/assets/schedule.svg" /> 6 hr 20 mins
            </div>
            <div>
              <img class="icon-img" src="@/assets/date.svg" />
              24 Lectures
            </div>
          </div>
          <div class="user-panel">
            <div class="username">
              <img class="user-img" src="@/assets/user-img2.jpg" />
              <span>Wanda Willson</span>
            </div>
            <div class="price">₹3000<span>₹3000</span></div>
          </div>
        </div>
      </div>
      <div class="card">
        <img class="card-img" src="@/assets/card-img3.jpg" />
        <div class="card-content-wrapper">
          <h3>Social Media Marketing - A to Z Content Marketing class 2021</h3>
          <p><span>46,995</span> Student</p>
          <div class="timeline">
            <div>
              <img class="icon-img" src="@/assets/schedule.svg" /> 11 hr 20 mins
            </div>
            <div>
              <img class="icon-img" src="@/assets/date.svg" />
              44 Lectures
            </div>
          </div>
          <div class="user-panel">
            <div class="username">
              <img class="user-img" src="@/assets/user-img3.jpg" />
              <span>Albert Hitler</span>
            </div>
            <div class="price">₹2000<span>₹2000</span></div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <RouterView />
</template>

<style scoped>
.logo {
  width: 150px;
}
.nav-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 90px;
  margin: 0 5rem;
}
.btn-container {
  height: 100%;
  display: flex;
  align-items: center;
}
.btn {
  margin: 0 0 0 1rem;
  padding: 0.7rem 1.2rem;
  outline: none;
  border: none;
  border-radius: 5px;
  color: #fff;
  background-color: rgba(1, 203, 99, 1);
  box-shadow: 0px 5px 15px #01cb6359;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
}
.btn:hover {
  background-color: rgba(1, 203, 99, 0.9);
  transition: all 0.2s ease-in-out;
}
.hero-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.left {
  height: 60vh;
  background: #01cb63;
  display: flex;
  justify-content: center;
  align-items: center;
}
.content-container {
  padding: 3rem;
}
.left h1 {
  color: #fff;
  font-weight: 600;
  font-size: 2rem;
}
.left h4 {
  font-style: italic;
  margin: 1.2rem 0;
  font-weight: 500;
}
.left h4 span {
  font-style: normal;
  color: #fff;
}
.right {
  height: 60vh;
}
.right img {
  object-fit: cover;
  width: 100%;
  height: 60vh;
  filter: brightness(80%) sepia(900%) hue-rotate(50deg) saturate(100%);
}
.black {
  background-color: #000000;
  color: #fff;
  font-style: italic;
  transition: all 0.2s ease-in-out;
  margin: 0;
  width: 50%;
}
.black:hover {
  background-color: rgb(29, 29, 29);
  box-shadow: 0px 5px 15px #00000028;
  transition: all 0.2s ease-in-out;
}
.stats-wrapper {
  background-image: url('@/assets/background1.svg');
  height: 20vh;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.stats-content h3 {
  color: #86919d;
  font-weight: 700;
}
.stats-content h1 {
  font-weight: 700;
  text-decoration: underline;
  text-decoration-color: #01cb63;
  text-underline-offset: 15px;
}
.courses-container {
  padding: 4rem 0;
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.courses-container p {
  color: #01cb63;
  font-style: italic;
}
.courses-container h1 {
  margin: 1rem 0 2rem 0;
  color: #1f2532;
  font-weight: 600;
}

.courses-wrapper {
  width: 80%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
}
.card {
  max-width: 300px;
  border: 1px solid #e6e6e6;
  border-radius: 15px;
  margin: 2rem;
}
.card .card-img {
  object-fit: cover;
  width: 100%;
  border-radius: 15px 15px 0px 0px;
}

.card-content-wrapper {
  padding: 1rem;
}
.card-content-wrapper h3 {
  font-weight: 700;
  font-size: 1.2rem;
}
.card-content-wrapper p {
  margin: 1rem 0;
  font-size: 0.9rem;
  font-style: italic;
}
.card-content-wrapper p > span {
  font-weight: 700;
  font-style: normal;
}
.timeline {
  display: flex;
  justify-content: space-between;
  align-items: center;

  font-size: 0.8rem;
  font-style: italic;
  color: #86919d;
}
.timeline > div {
  font-weight: 600;
  display: flex;
  align-items: center;
}
.user-panel {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.user-panel > div {
  display: flex;
  align-items: center;
  font-size: 1rem;
}
.username span {
  font-weight: 600;
  color: #000000;
}
.price {
  color: #01cb63;
  font-weight: 500;
}
.price span {
  text-decoration: line-through;
  color: #000000;
  margin-left: 5px;
  font-size: small;
}
.user-img {
  object-fit: cover;
  width: 50px;
  height: 50px;
  border-radius: 100%;
  margin: 10px 10px 10px 0;
}
</style>
