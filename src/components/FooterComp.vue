<template>
  <footer>
    <div class="footer-wrapper">
      <div>2021-2022 © Course Pro Private Limited</div>
      <div class="terms">
        <a href="#">Terms and Condition</a>
        <a href="#">Privacy Policy</a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComp',
}
</script>

<style scoped>
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 15vh;
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
.terms a {
  font-weight: bolder;
  margin: 0 1rem;
}
</style>
