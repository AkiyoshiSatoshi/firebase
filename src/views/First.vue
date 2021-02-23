<template>
  <div class="first">
    <h1>Home</h1>
    <Profile />
    <div class="home">
      <Home />
    </div>
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Profile from '../components/Profile.vue'
import Home from '../components/Home.vue'
import Footer from '../components/Footer.vue'

export default Vue.extend({
  name: 'First',
  components: {
    Profile,
    Home,
    Footer,
  }
})
</script>

<style scoped>

.first {
  height: 812px;
}

h1 {
  color: white;
  font-family: fantasy;
  font-size: 24px;
  padding-top: 50px;
  background: #72dbf0;
}

</style>