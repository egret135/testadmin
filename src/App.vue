<template>
  <div id="app">
    <el-container style="height: 100%" direction="vertical">
      <ElHeader />
      <el-container direction="horizontal">
        <ElAside />
        <ElMain />
      </el-container>
    </el-container>
  </div>
</template>

<script>
  import ElHeader from './components/Layout/ElHeader'
  import ElAside from './components/Layout/ElAside'
  import ElMain from './components/Layout/ElMain'

  export default {
    name: 'App',
    components: {
      ElHeader,
      ElAside,
      ElMain
    },
  }
</script>

<style lang="less" rel="stylesheet/less">
  @import "./styles/reset.less";
</style>

<style>
  body {
    margin: 0;
  }
  #app {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>
