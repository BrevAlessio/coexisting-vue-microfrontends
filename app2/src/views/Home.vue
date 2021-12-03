<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
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
    console.log('APP2 ROUTE ENTER')
  },
  beforeRouteLeave() {
    console.log('APP2 ROUTE LEAVE')
  },
}
</script>
