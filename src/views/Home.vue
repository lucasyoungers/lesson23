<template>
  <div class="home">
    <home-header></home-header>
    <home-body></home-body>
    <app-footer></app-footer>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import HomeHeader from '@/components/HomeHeader.vue'
import HomeBody from '@/components/HomeBody.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    HomeHeader,
    HomeBody,
    AppFooter
  }
}
</script>

<style>

</style>