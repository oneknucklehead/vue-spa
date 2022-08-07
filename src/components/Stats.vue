<template>
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
</template>
<script>
export default {
  name: `StatsComp`,
}
</script>
<style scoped>
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
</style>
