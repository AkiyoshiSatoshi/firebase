<template>
  <div class="login">
    <Title />
    <LoginWrap />
    <Return />
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Title from '../components/Title.vue'
import LoginWrap from '../components/LoginWrap.vue'
import Return from '../components/Return.vue'

export default Vue.extend({
  name: 'Login',
  components: {
    Title,
    LoginWrap,
    Return
  },
});
</script>

<style scoped>
.login {
  z-index: 0;
  background: url("../assets/765575ff84df6f5d40ba0d0321505d0b.jpg") no-repeat center;
  background-size: cover;
  position: relative;
  height: 812px;
  overflow: hidden;
  z-index: 0;
}

.login:before {
  content: '';
  background: inherit;
  -webkit-filter: blur(5px);
  -moz-filter: blur(5px);
  -o-filter: blur(5px);
  -ms-filter: blur(5px);
  filter: blur(2px);
  position: absolute;
  top: -5px;
  left: -5px;
  right: -5px;
  bottom: -5px;
  z-index: -1;
}

</style>