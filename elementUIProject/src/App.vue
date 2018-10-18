<template>
  <div id="app">
    <el-container>
      <el-main><router-view/></el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
#app {
  height:100%;
  .el-container{
    height:100%;
  }
}
</style>
