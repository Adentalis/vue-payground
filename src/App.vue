<script setup lang="ts">
const test = () => {
  console.log('er')
}
</script>

<template>
  <div>
    <h1 @click="test">asdsad</h1>
    <div class="content">
      <div class="item">x</div>
      <div class="item">x</div>
      <div class="item">x</div>

      <div class="item">x</div>
      <div class="item">x</div>

      <div class="item">x</div>
      <div class="item">x</div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  text-align: center;
  border: 2px red solid;
}

.content {
  border: 3px green solid;
  display: grid;
  grid-template-rows: 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}

.item {
  min-height: 200px;
  min-width: 200px;

  border: 3px yellow solid;
}
</style>
