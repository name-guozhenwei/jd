<template>
  <div class="layout">
    <!-- 头部 -->
    <div class="header">
      <div class="logo">
        <i></i>
      </div>
      <div class="serach">
        <i></i>
        <input type="serach" placeholder="iphoneX" />
      </div>
      <div class="login">
        <a href="#">登入</a>
      </div>
    </div>
    <router-view></router-view>
    <ul class="footer">
      <li>
        <a href="#">
          <img src="../../assets/footer01.png" alt="" />
        </a>
        <p>首页</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/footer02.png" alt="" />
        </a>
        <p>分类</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/footer03.png" alt="" />
        </a>
        <p>拼购</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/footer04.png" alt="" />
        </a>
        <p>购物车</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/footer05.png" alt="" />
        </a>
        <p>我的</p>
      </li>
    </ul>
  </div>
</template>

<script>
export default {}
</script>

<style lang='scss' scoped>
.layout {
  min-width: 320px;
  max-width: 640px;
  .header {
    width: 100%;
    // height: 40px;
    background-color: #d92829;
    padding: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0px;

    .logo {
      width: 70px;

      i {
        width: 57px;
        height: 23px;
        background: url("~@/assets/jd-sprites.png") 0 -109px;
        background-size: 200px 200px;
        background-position: 0 -109px;
        display: block;
        // margin: 0 auto;
      }
    }
    .serach {
      display: flex;
      flex: 1;
      position: relative;
      i {
        width: 21px;
        height: 21px;
        background: url("~@/assets/jd-sprites.png") -59px -109px;
        background-size: 200px 200px;
        background-position: -59px -109px;
        position: absolute;
        top: 5px;
        left: 5px;
      }
      input {
        width: 100%;
        height: 30px;
        border-radius: 15px;
        padding-left: 30px;
        font-size: 12px;
      }
    }
    .login {
      width: 50px;
      height: 40px;
      text-align: center;
      // align-items: center;
      line-height: 30px;
      a {
        font-size: 12px;
        color: #fff;
      }
    }
  }
  .footer {
    width: 100%;
    height: 50px;
    background-color: #fff;
    position: fixed;
    bottom: 0px;
    display: flex;
    min-width: 320px;
    max-width: 640px;
    padding-bottom: 50px;
    li {
      flex: 1;
      img {
        width: 65px;
        height: 50px;
      }
    }
  }
}
</style>
