<template>
  <section class="main-layout">
    <app-header />
    <!-- <router-link to="/">Home</router-link> | -->
    <!-- <router-link to="/about">About</router-link> -->
    <router-view/>
  </section>
</template>

<script>
import appHeader from './components/app-header.vue'
export default {
  name: 'app',
  data() {
    return {
      msg: 'A msg',
    }
  },
  components: {
    appHeader,
  },
}
</script>
