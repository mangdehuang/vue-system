<template>
  <div class="login">
      <div class="title">后台管理系统</div>
      <div class="ms-login">
        <el-form :module="form" ref="form">
          <el-form-item>
            <el-input placeholder="name"></el-input>
          </el-form-item>
          <el-form-item>
            <el-input placeholder="password"></el-input>
          </el-form-item>
          <el-form-item class="sub-btn">
            <el-button type="primary">登录</el-button>
          </el-form-item>
        </el-form>
      </div>
  </div>
</template>

<script>
    export default {
        data: function () {
            return {}
        },

        watch: {
            items: {
                handler: function () {

                },
                deep: true
            }
        },
        methods: {}
    }
</script>

<style>
  .login{
    background-color: #324157;
    width: 100%;
    height: 100%;
    position: relative;
  }
  .title{
    width: 100%;
    text-align: center;
    color: #ffffff;
    position: absolute;
    top: 50%;
    margin-top: -230px;
    font-size: 30px;
  }
  .ms-login{
    border-radius: 5px;
    width: 300px;
    position: absolute;
    left: 50%;
    top: 50%;
    margin-left: -190px;
    margin-top: -150px;
    height: 160px;
    padding: 40px;
    background-color: #ffffff;
  }
  .sub-btn button{
    width: 100%;
    height: 30px;
  }
</style>
