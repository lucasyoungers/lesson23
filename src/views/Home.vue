<template>
  <div class="home">
    <home-header></home-header>
    <home-body></home-body>
    <home-footer></home-footer>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeHeader from '@/components/HomeHeader.vue'
import HomeBody from '@/components/HomeBody.vue'
import HomeFooter from '@/components/HomeFooter.vue'

export default {
  name: 'home',
  components: {
    HomeHeader,
    HomeBody,
    HomeFooter
  }
}
</script>