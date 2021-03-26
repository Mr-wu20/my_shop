<template>
  <el-button type="info" @click="loginout">退出</el-button>
</template>

<script>
export default {
  methods: {
    loginout() {
      window.sessionStorage.clear()
      this.$router.push('/login')
    }
  }
}
</script>
<style lang="less" scoped></style>
