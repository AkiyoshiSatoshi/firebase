<template>
  <div class="profile">
    <div class="profile-wrap">
      <h2>Hello, {{ guest }}!</h2>
      <img src="../assets/logo.png" alt="" class="user-img">
    </div>
    <p>Where do you want to travel?</p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'Profile',
  data() {
    return {
      guest: "AKIYOSHISATOHI"
    };
  }
});
</script>

<style scoped>

.profile {
  background: #72dbf0;
  border-radius: 0  0 20px 20px;
  padding-top: 20px;
  padding-bottom: 50px;
}

.profile-wrap {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-end;
}

h2 {
  text-align: right;
  color: white;
  padding-right: 10px;
  font-family: fantasy;
  padding-top: 25px;
}

span {
  padding: 5px;
  color: white;
  font-family: fantasy;
}

.user-img {
  z-index: 100;
  border-radius: 50px;
  background: white;
  width: 15%;
}

p {
  padding-top: 15px;
  color: white;
  float: left;
  font-family: fantasy;
  font-size: 20px;
}

</style>