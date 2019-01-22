<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>8 YEARS OF DESIGN</h1>

      <p class="subtxt">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed, impedit.</p>
    </div>

    <div class="right-content img1">
      <button>
        <router-link to="/portfolio/one">Browse Work</router-link>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>

<style scoped>
.img1 {
  background: url("../assets/home.jpg");
}
</style>
