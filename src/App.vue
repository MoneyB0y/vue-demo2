<template>
  <div id="app">
    <keep-alive> <!-- 缓存的作用 -->
      <router-view/>  
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
