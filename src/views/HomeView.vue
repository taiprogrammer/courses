<template>
  <div>
    <HeaderComponent />
    <div class="container">
      <h1>Home</h1>
      <router-link to="/contato">Contato</router-link>
    </div>
  </div>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent.vue";
export default {
  name: "HomeView",
  components: {
    HeaderComponent,
  },
};
</script>

<style scoped lang="css">
.container {
  width: 80%;
  margin: 20px auto;
}
</style>
