<template>
  <div class="user">
    <user-header></user-header>
    <user-body></user-body>
    <user-footer></user-footer>
  </div>
</template>

<script>
import UserHeader from '@/components/UserHeader.vue'
import UserBody from '@/components/UserBody.vue'
import UserFooter from '@/components/UserFooter.vue'

export default {
  name: user,
  components: {
    UserHeader,
    UserBody,
    UserFooter
  }
}
</script>