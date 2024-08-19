<script setup>
import { ref, onMounted, onUnmounted } from "vue";
import Navigation from "./components/Navigation.vue";
import Hero from "./components/Hero.vue";
import Steps from "./components/Steps.vue";
import Conditions from "./components/Conditions.vue";
import Prices from "./components/Prices.vue";
import Reviews from "./components/Reviews.vue";
import Footer from "./components/Footer.vue";

const showNavigation = ref(false);

const checkScreenWidth = () => {
  showNavigation.value = window.innerWidth > 767;
};


onMounted(() => {
  checkScreenWidth();
  window.addEventListener("resize", checkScreenWidth);
});


onUnmounted(() => {
  window.removeEventListener("resize", checkScreenWidth);
});
</script>


<template>
    <div>
      
      <div className="mt-8 mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
          <Navigation v-if="showNavigation" />
          <Hero/>
        <Steps/>
        <Conditions/>
        <Reviews/>
        <Prices/>
      </div>

      <Footer/>
</div>
</template>

<style scoped>

</style>



