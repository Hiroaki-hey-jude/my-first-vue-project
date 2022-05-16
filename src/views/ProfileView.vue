<template>
  <div class="profile">
    <div class="profile-pic-container">
      <img src="@/assets/frog.jpg" alt="" />
      <img class="profile-pic" src="@/assets/hirohiro.jpg" alt="" />
      <img class="profile-pic" src="@/assets/snow.jpg" alt="" />
      <img class="profile-pic" src="@/assets/sky.jpg" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "ProfileView",
  data() {
    return {};
  },
};
</script>
<style scoped>
.profile-pic-container {
  display: grid;
  gap: 10px;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: 200px 100px 100px;
}
.profile-pic {
  width: 100%; /* ADD */
  height: 100%; /* ADD */
  object-fit: scale-down;
}
</style>