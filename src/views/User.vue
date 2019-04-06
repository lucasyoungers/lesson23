<template>
  <div class="about">
    <user-header></user-header>
    <user-body></user-body>
    <app-footer></app-footer>
  </div>
</template>

<script>
import UserHeader from '@/components/UserHeader.vue'
import UserBody from '@/components/UserBody.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
  name: 'user',
  components: {
    UserHeader,
    UserBody,
    AppFooter
  }
}
</script>