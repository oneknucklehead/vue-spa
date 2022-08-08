<template>
  <div class="compliments-container">
    <div class="compliments-content">
      <p class="pre-header">Testimonials</p>
      <h1 class="header">Check out What Our Students Think About Us</h1>
      <div class="compliments-wrapper">
        <div class="compliments">
          <p>
            It's a comprehensive online learning platform for everyone looking
            to learn and course pro. provinding this platform which is very
            beneficial for practicals. Students can revise everything at home
            like dissection and slides
          </p>
          <div class="user-container">
            <div class="user-profile">
              <img src="@/assets/user-img1.jpg" />
              <div class="user-info">
                <p class="name">Anshul Jain</p>
                <p>Yesterday</p>
              </div>
            </div>
            <img src="@/assets/quote.png" />
          </div>
        </div>

        <div class="compliments">
          <p>
            It's A Comprehensive Online Learning Platform For Everyone Looking
            To Learn And Course Pro. Provinding This Platform Which Is Very
            Beneficial For Practicals. Students Can Revise Everything At Home
            Like Dissection And Slides
          </p>
          <div class="user-container">
            <div class="user-profile">
              <img src="@/assets/user-img3.jpg" />
              <div class="user-info">
                <p class="name">Rajkumar Jain</p>
                <p>Yesterday</p>
              </div>
            </div>
            <img src="@/assets/quote.png" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ComplimentsComp',
}
</script>

<style scoped>
.compliments-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 75vh;
}
.compliments-content {
  width: 80%;
}
.compliments-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.compliments {
  max-width: 500px;
  margin: 2rem 0;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0px 20px 30px #1f25321a;
}

.compliments p {
  font-style: italic;
}
.user-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.user-container img {
  width: 50px;
  height: 40px;
}
.user-profile {
  display: flex;
  align-items: center;
}
.user-profile img {
  width: 50px;
  height: 50px;
  border-radius: 100%;
  margin: 1rem 1rem 1rem 0;
}
.user-profile .name {
  font-weight: bold;
}
</style>
