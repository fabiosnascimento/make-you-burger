<template>
  <Banner />
  <div class="main-container">
    <h1>MONTE O SEU BURGER</h1>
    <BurgerForm />
  </div>
</template>

<script>
  import Banner from "../components/Banner.vue";
  import BurgerForm from "../components/BurgerForm.vue";

 export default {
  components: {
    Banner,
    BurgerForm,
  }
 }
</script>
