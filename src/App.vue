<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style >
#app {
  height: 700px;
  display:flex;
  display: -webkit-flex;
  align-items:center;
  justify-content:center; 
}
</style>
