<template>
   <BannerVue />
   <div class="main-container">
      <h1>Monte o seu burger:</h1>
      <burger-form />
  </div>
</template>

<script>
  import BannerVue from "@/components/Banner.vue";
import BurgerForm from '@/components/BurgerForm.vue';

  export default {
    name: 'Home',

    components: {
      BannerVue,
        BurgerForm
    }
  }
// @ is an alias to /src

</script>
