<template>
  <div class="home">
    <div class="container">
      <h1>歡迎來到首頁</h1>
      <p>這是一個簡單的 Vue 網站範例。</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
.home {
  width: 100%;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  text-align: center;
}

h1 {
  margin-bottom: 20px;
  color: #333;
}
</style>
