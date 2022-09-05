<template>
  <div>
    <router-link to="/home">home</router-link>
    <router-link to="/about">about</router-link>
    <router-view />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
// import HelloWorld from 'components/HelloWorld.vue'
// import UserLogin from 'views/user-login/UserLogin.vue'

export default defineComponent({
  components: {},
  setup() {
    return {}
  }
})
</script>

<style scoped></style>
