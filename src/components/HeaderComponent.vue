<template>
  <header>
    <h1>¡Bienvenido!</h1>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  // Código del componente
}
</script>

<style scoped>
header {
  background-color: #333;
  color: white;
  padding: 10px 0;
}

nav {
  margin-top: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  margin-right: 10px;
}

nav a.router-link-exact-active {
  font-weight: bold;
}
</style>
