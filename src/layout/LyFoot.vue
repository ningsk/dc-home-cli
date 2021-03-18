<template>
  <footer class="ly-foot">
    <el-divider></el-divider>
  </footer>
</template>
<script>
export default {
  name: 'LyFoot',
  data() {
    return {}
  }
}
</script>

<style lang="scss" scoped>
.ly-foot {
  position: relative;
  width: 100%;
  height: 50px;
  user-select: none;
  color: #999999;
  padding-bottom: 5px;
  a {
    cursor: pointer;
    color: #999999;
    text-decoration: none;
    &:hover {
      color: #f5533d !important;
    }
  }

  .copyright {
    text-align: center;
    font-size: 0.5rem;
    color: #666666;
    a {
      color: #666666;
    }
  }
}
</style>
