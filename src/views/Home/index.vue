<template>
  <div class="home">
    <!-- 轮播图 -->
    <div class="swipre">
      <ul>
        <li>
          <a href="#">
            <img src="../../assets/banner01.jpg" alt="" />
          </a>
        </li>
      </ul>
    </div>
    <!-- 导航栏 -->
    <ul class="nav">
      <li>
        <a href="#">
          <img src="../../assets/nav01.png" alt="" />
        </a>
        <p>京东超市</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav02.png" alt="" />
        </a>
        <p>全球购</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav03.png" alt="" />
        </a>
        <p>服装城</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav04.png" alt="" />
        </a>
        <p>京东生鲜</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav05.png" alt="" />
        </a>
        <p>京东到家</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav06.png" alt="" />
        </a>
        <p>充值中心</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav07.png" alt="" />
        </a>
        <p>京东金融</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav08.png" alt="" />
        </a>
        <p>领劵</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav09.png" alt="" />
        </a>
        <p>物流查询</p>
      </li>
      <li>
        <a href="#">
          <img src="../../assets/nav10.png" alt="" />
        </a>
        <p>我的关注</p>
      </li>
    </ul>
    <!-- 京东快报 -->
    <div class="news">
      <div class="logo">
        <img src="../../assets/jd-news-tit.png" alt="" />
      </div>
      <div class="info">
        <a href="#"
          >京东快报京东快报京东快报京东快报京东快报京东快报京东快报京东快报京东快报</a
        >
      </div>
      <div class="more">
        <a href="#">| 更多</a>
      </div>
    </div>
    <!-- 秒杀 -->
    <div class="seckill">
      <div class="title">
        <div class="logo">
          <i></i>
          <span>京东秒杀</span>
        </div>
        <div class="time">
          <span>00</span>
          <span>:</span>
          <span>00</span>
          <span>:</span>
          <span>00</span>
        </div>
        <div class="more-seckill">
          <a href="#">更多秒杀 > </a>
        </div>
      </div>
      <div class="content">
      <ul class="goods">
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec01.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec02.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec03.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec04.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec05.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec06.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
        <li>
          <a href="#">
            <div class="pic">
              <img src="../../assets/sec07.jpg" alt="" />
            </div>
          </a>
          <p>¥ 1499</p>
          <p>¥ 1499</p>
        </li>
      </ul>
    </div>
    </div>
    <!-- 主会场 -->
    <ul class="main-meeting-place">
      <li>
        <a href="#"><img src="../../assets/item01.jpg" alt="" /></a>
      </li>
      <li>
        <a href="#"><img src="../../assets/item02.jpg" alt="" /></a>
      </li>
      <li>
        <a href="#"><img src="../../assets/item03.jpg" alt="" /></a>
      </li>
    </ul>
    <!-- 商品分类区域 -->
    <div class="goods-cart">
      <ul class="top">
        <li>
          <a href="#">
            <img src="../../assets/major_1.jpg" alt="" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../../assets/major_2.jpg" alt="" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../../assets/major_3.jpg" alt="" />
          </a>
        </li>
      </ul>
      <ul class="center">
        <li>
          <a href="#">
            <img src="../../assets/major_4.jpg" alt="" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../../assets/major_4.jpg" alt="" />
          </a>
        </li>
      </ul>
      <ul class="buttom">
        <li>
          <a href="#">
            <img src="../../assets/major_6.jpg" alt="" />
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../../assets/major_6.jpg" alt="" />
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>
<style lang='scss' scoped>
.home {
  // 轮播图
  .swipre {
    margin-top: 40px;
    width: 100%;

  }
  //  导航栏
  .nav {
    display: flex;
    flex-wrap: wrap;
    // justify-content: center;

    li {
      width: 20%;
      padding: 10px 0;

      img {
        width: 40px;
        height: 40px;
        margin: 0 auto;
      }
      p {
        text-align: center;
        font-size: 14px;
        padding: 8px 0;
      }
    }
  }
  // 京东快报
  .news {
    display: flex;
    align-items: center;
    width: 100%;
    height: 30px;
    background-color: #fff;
    border-radius: 10px;
    padding: 0px 10px;
    .logo {
      width: 78px;
    }
    .info {
      flex: 1;
      font-size: 12px;
      overflow: hidden;
      white-space: nowrap;
      text-overflow: ellipsis;
      margin-left: 5px;
    }
    .more {
      width: 38px;
      font-size: 12px;
      line-height: 30px;
    }
  }
  // 京东秒杀
  .seckill {
    margin-top: 10px;
    width: 100%;
    // height: 373px;
    background-color: #fff;
    // overflow: auto;
    overflow: hidden;

    .title {
      display: flex;

      .logo {
        display: flex;
        width: 94px;
        height: 30px;
        align-items: center;

        i {
          width: 22px;
          height: 22px;
          background: url("~@/assets/jd-sprites.png") -85px -109px;
          background-size: 200px 200px;
          margin-left: 10px;
        }
        span {
          width: 56px;
          font-size: 12px;
          color: #de2d2e;
          // padding-right: 5px;
        }
      }
      .time {
        flex: 1;
        margin-top: 7px;

        span {
          //  display: inline-block;
          float: left;
          &:nth-child(odd) {
            width: 18px;
            height: 18px;
            background: #000;
            font-size: 12px;
            color: #fff;
            text-align: center;
            border-radius: 5px;
          }
          &:nth-child(even) {
            width: 8px;
            text-align: center;
            font-size: 12px;
          }
        }
      }
      .more-seckill {
        font-size: 12px;
        margin-top: 7px;
        margin-right: 15px;
      }
    }
    .content {
      overflow: auto;
    .goods {
      display: flex;
      width: 609px;
      background-color: #fff;
      margin-top: 10px;

      li {
        width: 87px;

        .pic {
          border-right: 1px solid #ccc;
          &:nth-last-of-type() {
            border: 0;
          }
          img {
            width: 60px;
            height: 60px;
            margin: 5px auto;
          }
        }

        p {
          text-align: center;
          font-size: 12px;
          text-align: center;
          &:nth-of-type(1) {
            color: #c91719;
            font-weight: 700;
          }
          &:nth-of-type(2) {
            color: #969696;
            text-decoration: line-through;
          }
        }
      }
    }
  }
  }
  // 主会场
  .main-meeting-place {
    display: flex;

    // width: 100%;
    li {
      // width: 33%;
      flex: 1;
    }
  }
  // 商品分类
  .goods-cart {
    // display: flex;
    margin-bottom: 50px;
    .top,
    .center,
    .buttom {
      display: flex;
      li {
        flex: 1;
      }
    }
  }
}
</style>
