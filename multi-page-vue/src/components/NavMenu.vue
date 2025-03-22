<template>
  <nav class="nav-menu">
    <div class="menu-container">
      <router-link to="/">首頁</router-link>
      <router-link to="/about">關於我們</router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavMenu",
};
</script>

<style scoped>
.nav-menu {
  background-color: #ffffff;
  padding: 15px 0;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 100;
}

.menu-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.nav-menu a {
  color: #333;
  text-decoration: none;
  margin-right: 20px;
  font-weight: 500;
}

.nav-menu a.router-link-active {
  color: #3498db;
  border-bottom: 2px solid #3498db;
}
</style>
