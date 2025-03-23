<template>
  <div class="container">
    <div class="box"></div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
body, html {
  margin: 0;
  padding: 0;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f0f0f0;
}

.box {
  width: 100px;
  height: 100px;
  background-color: black;
}
</style>