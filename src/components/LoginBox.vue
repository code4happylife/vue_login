<template>
  <h1>登录页面</h1>
  <div class="login_box">
    <el-form :model="form" label-width="120px" style="width: 100%">
      <el-form-item label="用户名">
        <el-input v-model="form.name"/>
      </el-form-item>
      <el-form-item label="密码">
        <el-input v-model="form.pwd"/>
      </el-form-item>
      <el-form-item>
        <el-button type="primary" @click="onSubmit">登录</el-button>
        <el-button>取消</el-button>
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  name: "LoginBox",
  data() {
    return {
      form: {
        name: "",
        pwd: ""
      }
    }
  },
  methods: {
    onSubmit() {
      alert('login success!')
    }
  }
}
</script>

<style scoped>
.login_box {
padding: 0px 30px ;
}
</style>