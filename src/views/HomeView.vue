<template>
  <div class="home">
    <div class="vue-image">
      <img alt="Vue logo" src="../assets/logo.png" />
    </div>
    <div>
      <p class="about-me">about me</p>
      <p>
        Highly motivated web and mobile app developer, <br />currently learning
        vue.js. I made this portofolio website <br />using vue.js to get better
        understanding.<br />
        I want the TabaTaba!
      </p>
    </div>
    <div class="jimcy">
      <img src="@/assets/jimcy.jpg" alt="" />
    </div>
  </div>
</template>

<style scoped>
.home {
  display: flex;
  flex-direction: column;
}
.vue-image {
  margin: auto;
}
.about-me {
  font-size: 50px;
}
.jimcy {
  margin-top: 50px;
  margin-bottom: 200px;
}
</style>

