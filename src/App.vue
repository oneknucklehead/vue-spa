<script>
import HeaderComp from './components/HeaderComp.vue'
import HomeHero from './components/HomeHero.vue'
import Stats from './components/Stats.vue'
export default {
  name: `app`,
  data() {
    return {
      name: ``,
      email: ``,
      phone: ``,
      subject: ``,
      message: ``,
    }
  },
  components: { HeaderComp, HomeHero, Stats },
}
</script>

<template>
  <HeaderComp />
  <HomeHero />
  <Stats />
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

  <div class="ideas-container">
    <div class="ideas-content">
      <p class="pre-header">Top Earners</p>
      <h1 class="header">Transforming Your Ideas Into Reality</h1>
      <div class="people-wrapper">
        <div class="people">
          <img src="@/assets/people1.png" />
          <p class="money">₹8,00,000</p>
        </div>
        <div class="people">
          <img src="@/assets/people2.png" />
          <p class="money">₹6,00,000</p>
        </div>
        <div class="people">
          <img src="@/assets/people3.png" />
          <p class="money">₹5,00,000</p>
        </div>
      </div>
    </div>
  </div>

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

  <div class="contact-container">
    <p class="pre-header">Contact Us</p>
    <h1 class="header">Reach Out with any question you have</h1>

    <div class="contact-wrapper">
      <div class="contacts">
        <h1 class="header">Contact Information</h1>
        <div class="contact">
          <img src="@/assets/msg-icon.png" />
          <p>contact@coursepro.com</p>
        </div>
        <div class="contact">
          <img src="@/assets/call-icon.png" />
          <p>1800-562-895, 1800-869-877</p>
        </div>
        <div class="contact">
          <img src="@/assets/location-icon.png" />
          <p>102 Street, India</p>
        </div>
        <h1 class="header">Social Media Channel</h1>
        <div class="socials">
          <img src="@/assets/Facebook.png" />
          <img src="@/assets/Twitter.png" />
          <img src="@/assets/Github.png" />
          <img src="@/assets/Linkedin.png" />
        </div>
      </div>
      <div class="form">
        <h1 class="header">
          Fill up the form and our team will get back to you within 24 hours
        </h1>
        <div class="contact1">
          <input v-model="name" placeholder="Name" />
          <input v-model="email" placeholder="Email" />
        </div>
        <div class="contact1">
          <input v-model="phone" placeholder="Phone" />
          <input v-model="subject" placeholder="Subject" />
        </div>
        <textarea v-model="message" placeholder="Message"></textarea>
        <button class="btn black">Submit</button>
        <div>
          Message: {{ message }} name: {{ name }} phone: {{ phone }} email:{{
            email
          }}
          subject:{{ subject }}
        </div>
      </div>
    </div>
  </div>
  <footer>
    <div class="footer-wrapper">
      <div>2021-2022 © Course Pro Private Limited</div>
      <div class="terms">
        <p>Terms and Condition</p>
        <p>Privacy Policy</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.courses-container {
  padding: 4rem 0;
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.pre-header {
  color: #01cb63;
  font-style: italic;
}
.header {
  margin: 1rem 0 2rem 0;
  color: #1f2532;
  font-weight: 600;
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
.ideas-container {
  display: flex;
  justify-content: center;
  align-items: center;
}
.ideas-content {
  width: 80%;
}
.people-wrapper {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.people {
  margin: 2rem 0;
}
.money {
  padding: 0 0 0 10px;
  font-weight: 700;
  line-height: 80px;
  border-left: 0.8rem solid #01cb63;
  height: 80px;
}
.compliments-container {
  display: flex;
  justify-content: center;
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
.contact-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.contact-wrapper {
  width: 80%;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}
.contacts {
  /* width: auto; */
  max-width: 500px;
}
.contacts img {
  height: 80px;
  width: 80px;
}

.contact {
  display: flex;
  align-items: center;
}
.contact p {
  font-weight: bold;
}
.socials img {
  width: 50px;
  height: 50px;
  margin: 10px;
}
.form {
  display: flex;
  flex-direction: column;
  /* width: auto; */
  max-width: 500px;
}
.form-header {
  font-weight: bolder;
  font-size: 1.2rem;
}
.contact1 {
  display: flex;
}
input {
  margin-right: 10px;
  padding: 15px;
  border: none;
  border-bottom: 2px solid #01cb63;
  outline: none;
}
textarea {
  margin: 1.5rem 0;
  border: 2px solid #01cb63;
  outline: none;
}
@media only screen and (max-width: 1010px) {
  .form,
  .contacts {
    max-width: none;
  }
  .contact-wrapper {
    display: block;
  }
}

footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px;
}
.footer-wrapper {
  display: flex;
  justify-content: space-between;
  width: 80%;
}
footer div {
  font-weight: bolder;
}
.terms {
  display: flex;
}
.terms p {
  font-weight: bolder;
  margin: 0 1rem;
}
</style>
