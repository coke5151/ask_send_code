<script>
import NavMenu from "./components/NavMenu.vue";

export default {
  name: "App",
  components: {
    NavMenu,
  },
};
</script>

<template>
  <div id="app">
    <NavMenu />
    <main class="content">
      <router-view />
    </main>
  </div>
</template>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #ffffff;
}

.content {
  padding: 70px 20px 20px;
  width: 100%;
  box-sizing: border-box;
}
</style>
