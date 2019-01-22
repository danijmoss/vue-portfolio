<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>ABOUT ME</h1>
      <p class="subtxt">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Odit, laudantium.</p>

      <button>
        <router-link to="/portfolio/one">LOOK AT MY WORK</router-link>
      </button>
    </div>
    <div class="right-content">
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolore sequi in libero porro, enim tempora eius rem commodi eaque molestias corporis delectus pariatur dicta! Magnam soluta quibusdam amet. Quasi, nesciunt.</p>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolore sequi in libero porro, enim tempora eius rem commodi eaque molestias corporis delectus pariatur dicta! Magnam soluta quibusdam amet. Quasi, nesciunt.</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.left-content {
  background-color: #ffe476;
}

.right-content {
  background: #fff;
  padding: 50px;
  margin-top: 80px;
  display: block;
}

button {
  font-size: 1.5em;
  margin-top: 100px;
}

.subtxt {
  font-size: 1.5em;
  margin-top: 30px;
}
</style>

