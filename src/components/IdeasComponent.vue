<template>
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
</template>
<script>
export default {
  name: 'IdeasComponent',
}
</script>
<style scoped>
.ideas-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 75vh;
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
</style>
