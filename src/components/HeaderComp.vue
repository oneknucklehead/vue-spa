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
</template>

<script>
export default {
  name: `HeaderComp`,
}
</script>

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
</style>
