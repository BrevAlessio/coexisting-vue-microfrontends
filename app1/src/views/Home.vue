<template>
  <div class="home">
    <div>
      <img alt="Vue logo" src="../assets/logo.png">
    </div>
    <router-link to="/app2/about">App2's about page</router-link>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  beforeRouteEnter() {
    console.log('APP1 ROUTE ENTER')
  },
  beforeRouteLeave() {
    console.log('APP1 ROUTE LEAVE')
  },
}
</script>
