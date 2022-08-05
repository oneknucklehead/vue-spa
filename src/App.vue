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
}
.btn-container {
  height: 100%;
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
}
.btn:hover {
  background-color: rgba(1, 203, 99, 0.9);
}
</style>
