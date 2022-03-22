<template>
  <div class="bm-header">
    <el-menu :default-active="defaultActive" class="el-menu-demo" mode="horizontal">
      <el-menu-item index="index">
        <nuxt-link to="/">首页</nuxt-link>
      </el-menu-item>
      <el-menu-item index="test ">
        <nuxt-link to="/test">测试页</nuxt-link>
      </el-menu-item>
    </el-menu>
  </div>
</template>

<script>
export default {
  data() {
    return {
      defaultActive: 'index'
    }
  }
}
</script>

<style scoped>

</style>
