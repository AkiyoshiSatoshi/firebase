<template>
  <div class="footer">
    <div class="footer-wrap">
      <img src="../assets/Orion_house.svg" alt="" class="footer-img">
    </div>
    <div class="footer-wrap">
      <img src="../assets/Orion_map-marker.svg" alt="" class="footer-img">
    </div>
    <div class="footer-wrap">
      <img src="../assets/Orion_team.svg" alt="" class="footer-img">
    </div>
    <div class="footer-wrap">
      <img src="../assets/Orion_setting.svg" alt="" class="footer-img">
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  
})
</script>

<style scoped>

.footer {
  width: 100%;
  background: #72dbf0;
  border-radius: 10px 10px 0 0;
  display: flex;
  justify-content: space-around;

}

.footer-wrap {
  
}

.footer-img {
  padding: 10px 5px;
  width: 35%;
}
</style>