<template>
  <div class="home">
    <Title />
    <GoogleLogin />
    <Return />
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import GoogleLogin from '../components/GoogleLogin.vue';
import Title from '../components/Title.vue'
import Return from '../components/Return.vue'

export default Vue.extend({
  name: 'Home',
  components: {
    GoogleLogin,
    Title,
    Return
  },
});
</script>

<style scoped>
.home {
  z-index: 0;
  height: 812px;
}

body {
  background-image: url("");
}

</style>