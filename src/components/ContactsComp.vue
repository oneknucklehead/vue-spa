<template>
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
          <a href="#"><img src="@/assets/Facebook.png" /></a>
          <a href="#"> <img src="@/assets/Twitter.png" /></a>
          <a href="#"><img src="@/assets/Github.png" /></a>
          <a href="#"><img src="@/assets/Linkedin.png" /></a>
        </div>
      </div>
      <div class="form">
        <h1 class="header">
          Fill up the form and our team will get back to you within 24 hours
        </h1>
        <form>
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
        </form>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'ContactsComp',
  data() {
    return {
      name: ``,
      email: ``,
      phone: ``,
      subject: ``,
      message: ``,
    }
  },
}
</script>
<style scoped>
.contact-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 75vh;
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
form {
  height: 100%;
  display: flex;
  flex-direction: column;
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
.black {
  background-color: #000000;
  color: #fff;
  font-style: italic;
  transition: all 0.2s ease-in-out;
  margin: 0;
  box-shadow: 0px 5px 15px #00000028;

  width: 50%;
}
.black:hover {
  background-color: rgb(29, 29, 29);
  transition: all 0.2s ease-in-out;
}
</style>
