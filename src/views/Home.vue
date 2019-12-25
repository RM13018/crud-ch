<template>
  <div class="home">
    <AppBar/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import AppBar from '@/components/AppBar.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
    AppBar
  }
}
</script>
