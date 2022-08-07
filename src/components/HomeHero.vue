<template>
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
</template>

<script>
export default {
  name: `HomeHero`,
}
</script>
<style scoped>
.hero-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.left {
  background: #01cb63;
  display: flex;
  justify-content: center;
  align-items: center;
}
.content-container {
  padding: 5rem;
  width: 80%;
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
  /* height: 60vh; */
}
.right img {
  object-fit: cover;
  width: 100%;
  height: 100%;
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
</style>
