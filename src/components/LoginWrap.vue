<template>
  <div class="login-wrap">
    <p>Login Account</p>
    <div class="register">
      <PhoneLogin />
    </div>
    <p class="">or</p>
    <div class="select-google">
      <GoogleLogin />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import PhoneLogin from '../components/PhoneLogin.vue'
import GoogleLogin from '../components/GoogleLogin.vue'

export default Vue.extend({
  components: {
    GoogleLogin,
    PhoneLogin
  }
})
</script>

<style scoped>

.login-wrap {
  margin: 100px auto;
  width: 85%;
  border-radius: 30px;
  background: white;
  padding: 30px 0;
  border: 1px solid #45a7bb;
}

.login-wrap p {
  font-family: fantasy;
  font-size: 24px;
  margin-bottom: 20px;
  color: #45a7bb;
}

</style>