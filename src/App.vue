<template>
  <el-container style="height: 100%" direction="vertical">
    <ElHeader />
    <el-container direction="horizontal">
      <el-aside width="200px">Aside</el-aside>
      <el-main>
        <router-view/>
      </el-main>
    </el-container>
  </el-container>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
  .el-aside {
    background-color: #D3DCE6;
    color: #333333;
  }
  .el-main {
    background-color: #E9EEF3;
    color: #333333;
  }
  * {
    margin: 0;
    padding: 0;
    height: 100%;
  }
</style>
