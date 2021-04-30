<template>
  <div>
    <div class="nav">
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/excersise-01">Excersise 01</nuxt-link></li>
      </ul>
    </div>
    <Nuxt />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

* {
  margin: 0;
  font-family: 'Poppins', sans-serif;
}
.nav {
  position: fixed;
  top: 10px;
  left: 10px;
}

a:link {
  text-decoration: none;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

li a {
  display: block;
}
</style>
