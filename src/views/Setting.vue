<template>
  <div class="view">
    <h1>Setting</h1>
    <div class="updater">
      <input type="text" v-model="displayName" ref="nameInput" placeholder="DisplayName" />
    </div>
    <div class="updater">
      <input type="text" v-model="imgURL" ref="imgInput" placeholder="image input" >
    </div>
    <button>Update</button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: "Setting",
  methods: {
    /*const displayName = ref("");
    const imgURL = ref("");
    return { displayName, imgURL };*/
    function() {
      this.$refs.imgInput
    }
  }
})
</script>

<style scoped>

.view {
  height: 812px;
  background: white;
}

h1 {
  font-family: fantasy;
  font-size: 24px;
  padding-top: 200px;
  margin-bottom: 20px;
  color: #45a7bb;
}

.updater {
  margin: 0 auto;
  padding: 10px 20px;
  width: 70%;
  display: flex;
  flex-wrap: wrap;
  background: white;
  border-radius: 10px;
  margin-bottom: 30px;
  border: 1px solid #45a7bb;
}

.updater label {
  color: #45a7bb;
  padding: 10px 0;
}

.updater input {
  width: 100%;
}

button {
  margin-top: 10px;
  border: none;
  background: white;
  border-radius: 10px;
  color: #45a7bb;
  padding: 10px 20px;
  border: 1px solid #45a7bb;
}

</style>