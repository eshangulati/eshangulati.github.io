<template>
  <div class="app">
    <LoginPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import LoginPage from '@/components/LoginPage.vue'

export default {
  name: 'LoginView',
  components: {
    LoginPage
  }
}
</script>
