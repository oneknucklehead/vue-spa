<template>
  <div class="courses-container">
    <p class="pre-header">Courses</p>
    <h1 class="header">Our Most Popular Courses</h1>
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
</template>

<script>
export default {
  name: 'CoursesContainer',
}
</script>
<style scoped>
.courses-container {
  padding: 4rem 0;
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.courses-wrapper {
  width: 94%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
}
.card {
  max-width: 350px;
  border: 1px solid #e6e6e6;
  border-radius: 15px;
  margin: 2rem;
}
.card .card-img {
  object-fit: cover;
  width: 100%;
  height: 250px;
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
