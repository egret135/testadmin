<template>
  <el-header>
    WDNMD
  </el-header>
</template>

<script>
  export default {
    data() {
      return {
        activeIndex: '1',
        activeIndex2: '1'
      }
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
  }
</script>

<style scoped>
  .el-header {
    background-color: #545c64;
    color: #fff;
    line-height: 60px;
    padding: 0 0;
  }
</style>
