<template>
  <div class="login-wrap">
    <el-form class="login-form" label-position="top" label-width="80px">
      <h2>用户登录</h2>
      <el-form-item label="用户名">
        <el-input ></el-input>
      </el-form-item>
      <el-form-item label="密码">
        <el-input ></el-input>
      </el-form-item>
      <el-button  class="login-btn" type="success">登录</el-button>
    </el-form>
  </div>
</template>

<script>
export default {};
</script>

<style>
.login-wrap {
  height: 100%;
  background-color: #324152;
  display: flex;
  justify-content: center;
  align-items: center;
}
.login-form {
  background-color: #ffffff;
  border-radius: 5px;
  width: 400px;
  padding: 30px;
}
.login-btn {
  width: 100%;
}
</style>