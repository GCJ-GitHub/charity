<template>
<el-menu theme="dark" :default-active="activeIndex"
  class="el-menu-demo" mode="horizontal" @select="handleSelect">
    <el-menu-item index="1">首页</el-menu-item>
    <el-menu-item index="2">组织信息</el-menu-item>
    <el-menu-item index="3">项目信息</el-menu-item>
    <el-menu-item index="4">关于我们</el-menu-item>
    <el-menu-item index="5">登录</el-menu-item>
</el-menu>
</template>

<script>
export default {
  name: 'mynavbar',
  data () {
    return {
      activeIndex: '1',
      activeIndex2: '1'
    }
  },
  methods: {
    handleSelect (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>

<style>
</style>
