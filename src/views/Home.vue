<template>
  <div class="home">
    <home-header></home-header>
    <home-body></home-body>
    <app-footer></app-footer>
  </div>
</template>

<script>
import HomeHeader from "@/components/HomeHeader.vue";
import HomeBody from "@/components/HomeBody.vue";
import AppFooter from "@/components/AppFooter.vue";

export default {
  name: "home",
  components: {
    HomeHeader,
    HomeBody,
    AppFooter
  }
};
</script>

<style>
section {
  display: flex;
  flex-direction: column;
  padding: 12px;
  margin: 12px;
}

section p,
details {
  margin: 6px;
  padding: 6px;
  line-height: 150%;
}
</style>