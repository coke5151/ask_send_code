<template>
  <div class="about">
    <div class="container">
      <h1>關於我們</h1>
      <p>這是關於我們的頁面，您可以在這裡添加更多資訊。</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style scoped>
.about {
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
