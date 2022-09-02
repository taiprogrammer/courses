<template>
  <div>
    <header>
      <div class="container">
        <div class="logo">
          <h1>Router Courses</h1>
        </div>
        <nav>
          <router-link tag="a" to="contato">Login</router-link>
          <router-link tag="a" to="contato">Cadastro</router-link>
        </nav>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "HaederComponent",
};
</script>

<style scoped lang="css">
header {
  padding: 15px 0;
  background: rgba(0, 0, 0, 0.096);
}

.container {
  width: 80%;
  display: flex;
  margin: 0 auto;
  align-items: center;
  justify-content: space-between;
}

.container .logo {
  font-family: Verdana, sans-serif;
}

nav a {
  margin: 0 10px;
  color: #751b6e;
  text-decoration: none;
}
</style>