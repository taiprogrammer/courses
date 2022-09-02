<template>
  <div>
    <HeaderComponent />
    <div class="container">
      <h1>Contato</h1>
      <router-link to="/">Home</router-link>
    </div>
  </div>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent.vue";
export default {
  name: "ContactView",
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