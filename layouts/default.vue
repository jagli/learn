<template>
  <div>
    <div class="nav">
      <nuxt-link to="/">Home</nuxt-link>
      <nuxt-link to="/excersise-01">Excersise 01</nuxt-link>
    </div>
    <Nuxt />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

* {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  #app {
    font-family: 'Poppins', sans-serif;
  }
}
.nav {
  position: fixed;
  top: 10px;
  left: 10px;
  z-index: 100;
}
</style>
