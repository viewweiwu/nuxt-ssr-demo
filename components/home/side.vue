<style lang="stylus">
.container-side {
  width 240px
  margin-left: 25px
}
.container-side-card {
  padding 15px
  box-shadow 0 1px 2px 0 rgba(0, 0, 0, .05)
  background-color #fff
}
.card-login {
  h3 {
    font-size 14px
    margin-bottom 6px
  }
  .sub {
    font-size 14px
    margin-bottom 16px
  }
  .el-form-item {
    margin-bottom 10px
  }
  .el-input__inner {
    padding 7px 9px
    font-size 16px
    background-color #fbfbfb
    border 1px solid #f4f4f4
    border-radius 2px
    &::placeholder {
      color #90979c
    }
  }
}
</style>

<template>
  <div class="container-side">
    <div class="container-side-card card-login">
      <h3>掘金 - juejin.im</h3>
      <p class="sub">一个帮助开发者成长的社区</p>
      <el-form>
        <el-form-item>
          <el-input placeholder="昵称"></el-input>
        </el-form-item>
        <el-form-item>
          <el-input placeholder="邮箱 / 手机"></el-input>
        </el-form-item>
        <el-form-item>
          <el-input placeholder="密码"></el-input>
        </el-form-item>
      </el-form>
    </div>
  </div>
</template>