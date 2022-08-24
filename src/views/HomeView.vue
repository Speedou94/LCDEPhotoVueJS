<template>
  <div class="home">
    <img alt="Bannière" src="../assets/img/banniere.jpg" />
  </div>
  <cartes />
  <accueil />
</template>

<script>
// @ is an alias to /src
import Accueil from "@/components/Accueil.vue";
import Cartes from "@/components/Cartes.vue";
export default {
  name: "HomeView",
  components: {
    Accueil,
    Cartes,
  },
};
</script>

<style>
.home {
  margin-top: 10rem;
  margin-bottom: -4rem;
}
</style>
