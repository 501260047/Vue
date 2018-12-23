<template>
  <div>
    <p>这是个人中心</p>
    <router-link to="/userCenter/userInfo">用户信息</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
  export default {}
</script>

<style scoped>
  p{
    display: block;
    background: #d6e9c6;
  }
</style>
