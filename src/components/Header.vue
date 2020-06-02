<template>
  <div class="header">
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>|
      <router-link to="/work">Work</router-link>
    </div>
    <h1>{{ msg }}</h1>
    <!-- <div class="image">
      <img alt="top画像" src="../assets/top-bg.jpg" />
    </div>-->
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<style lang="scss">
.header {
  width: 100%;
}

.image {
}

.image img {
  width: 100%;
}
</style>
