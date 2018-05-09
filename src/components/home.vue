<template>
  <div class="">
    <div class="chunk1">
      <img src="../assets/banner.png" style="width:100%; z-index: -1;" alt="">
      <div class="container">
        <div id="navbar" class="hidden-xs hidden-sm">
          <div class="row">
            <div class="col-md-7">
              <div class="col-md-10 col-md-offset-2">
                <img src="../assets/logo.png" style="width: 17.6rem;">
              </div>
            </div>
            <div class="col-md-5" style="font-size:1.56rem;">
              <div class="row">
                <div class="col-md-3">
                  <span @click="scrollTo()">首页</span>
                </div>
                <div class="col-md-3">
                  <span @click="scrollTo('.chunk3')">系统特点</span>
                </div>
                <div class="col-md-3">
                  <span @click="scrollTo('.chunk4')">功能模块</span>
                </div>
                <div class="col-md-3">
                  <span @click="scrollTo('.chunk5')">联系我们</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="chunk2">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <div class="text1">作为通用航空领域的软件系统方案提供商，我们拥有</div>
            <div class="text2">丰富的通航业务经验、完整的软件开发团队、以及经验丰富的工程师</div>
          </div>
          <div class="col-md-4">
            <div class="botton">
              <img src="../assets/phone.png" alt="" style="margin:-1.2rem 1.5rem 0 2.76rem;">
              <span class="num">010-62662080</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="chunk3">
      <div class="container">
        <div>
          <div class="title">系统特点</div>
          <div style="text-align:center;margin-bottom:6rem;"><img src="../assets/line.png" alt=""></div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <div class="row">
              <div class="col-md-4" style="padding-bottom:2rem;">
                <div class="row">
                  <div class="col-md-2" style="text-align: center;">
                    <img src="../assets/icon1.png" alt="">
                  </div>
                  <div class="col-md-10">
                    <div class="lable">实用性</div>
                    <div class="synopsis">系统上线2年，实现了无纸化办公 <br>满足业务各方面要求，得到用户好评</div>
                  </div>
                </div>
              </div>
              <div class="col-md-4" style="padding-bottom:2rem;">
                <div class="row">
                  <div class="col-md-2" style="text-align: center;">
                    <img src="../assets/icon2.png" alt="">
                  </div>
                  <div class="col-md-10">
                    <div class="lable">安全性</div>
                    <div class="synopsis">内外网隔离，保证系统的安全性<br> 数据热备份，保证数据的安全性</div>
                  </div>
                </div>
              </div>
              <div class="col-md-4" style="padding-bottom:2rem;">
                <div class="row">
                  <div class="col-md-2" style="text-align: center;">
                    <img src="../assets/icon3.png" alt="">
                  </div>
                  <div class="col-md-10">
                    <div class="lable">稳定性</div>
                    <div class="synopsis">系统长时间运行，经受了时间和 <br> 数据的考验，系统运行平稳</div>
                  </div>
                </div>
              </div>
              <div class="col-md-4" style="padding-bottom:2rem;">
                <div class="row">
                  <div class="col-md-2" style="text-align: center;">
                    <img src="../assets/icon4.png" alt="">
                  </div>
                  <div class="col-md-10">
                    <div class="lable">准确性</div>
                    <div class="synopsis">系统自动校验，保证数据一致性 <br> 系统自动计算，杜绝人为出错可能性 <br> 非法数据无法录入到系统里</div>
                  </div>
                </div>
              </div>

              <div class="col-md-4" style="padding-bottom:2rem;">
                <div class="row">
                  <div class="col-md-2" style="text-align: center;">
                    <img src="../assets/icon5.png" alt="">
                  </div>
                  <div class="col-md-10">
                    <div class="lable">效率提升</div>
                    <div class="synopsis">电子化的录入、自动化计算<br> 自动提示基础数据，减轻记忆负担 <br> 自动生成报表，为决策提供支持<br> 通过数据分析找到系统优化点，提高效率</div>
                  </div>
                </div>
              </div>

              <div class="col-md-4" style="padding-bottom:2rem;">
                <div class="row">
                  <div class="col-md-2" style="text-align: center;">
                    <img src="../assets/icon6.png" alt="">
                  </div>
                  <div class="col-md-10">
                    <div class="lable">实时性</div>
                    <div class="synopsis">实时提供现场数据，<br>为指挥大厅决策提供依据</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="chunk4">
      <div class="container">
        <div>
          <div class="title">功能模块</div>
          <div style="text-align:center;margin-bottom:6rem;"><img src="../assets/line.png" alt=""></div>
        </div>
        <div class="row">
          <div class="col-md-5">
            <ul id="hp-indicators">
              <li data-target="#carousel-example-generic" data-slide-to="0" class="active">
                基础数据管理
              </li>
              <li data-target="#carousel-example-generic" data-slide-to="1">
                生产计划管理
              </li>
              <li data-target="#carousel-example-generic" data-slide-to="2">
                生产监控
              </li>
              <li data-target="#carousel-example-generic" data-slide-to="3">
                业务统计分析
              </li>
              <li data-target="#carousel-example-generic" data-slide-to="4">
                大屏显示
              </li>
            </ul>
          </div>
          <div class="col-md-7">

            <div class="mac">
              <div id="carousel-example-generic" class="carousel slide" data-interval="5000" data-ride="carousel">

                <!-- Wrapper for slides -->
                <div class="carousel-inner" role="listbox">
                  <div class="item active" data-active="1">
                    <img src="../assets/hp1.png" alt="...">
                  </div>
                  <div class="item">
                    <img src="../assets/hp2.png" alt="...">
                  </div>
                  <div class="item">
                    <img src="../assets/hp3.png" alt="...">
                  </div>
                  <div class="item">
                    <img src="../assets/hp4.png" alt="...">
                  </div>
                  <div class="item">
                    <img src="../assets/hp5.png" alt="...">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="chunk5">
      <div class="container">
        <div>
          <div class="title">联系我们</div>
          <div style="text-align:center;margin-bottom:6rem;"><img src="../assets/line.png" alt=""></div>
        </div>
        <div class="row">
          <div class="col-md-5">
            <div class="introduce">
              <div class="lable">北京新锐友信软件技术开发公司</div>
              <div><img src="../assets/point.png"> 提供通用航空领域软件系统解决方案</div>
              <div><img src="../assets/point.png"> 丰富的通航业务经验</div>
              <div><img src="../assets/point.png"> 完整的软件开发团队</div>
              <div><img src="../assets/point.png"> 经验丰富的工程师</div>
            </div>
          </div>
          <div class="col-md-2 hidden-xs  hidden-sm">
            <div class="line"></div>
          </div>
          <div class="col-md-5" style="text-align: center;font-size: 1.8rem;line-height: 4.8rem;padding-top:1.2rem;">
            <div>联系电话</div>
            <div class="tel">010-62662080</div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="container">
        <div>Copyright © 2013-2018 新锐友信</div>
        <div>京ICP备14033594号-1</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  data() {
    return {};
  },
  mounted() {
    $(window).scroll(function() {
      if ($(this).scrollTop() > 200) {
        $("#navbar").css({
          position: "fixed",
          top: "0",
          background: "#fff",
          color: "#43B1F8",
          "box-shadow": "0 2px 4px rgba(0, 0, 0, 0.14)"
        });
      } else {
        $("#navbar").css({
          position: "absolute",
          top: "7rem",
          background: "none",
          color: "#878787",
          "box-shadow": "0 0px 0px rgba(0, 0, 0, 0.14)"
        });
      }
    });
    $("#carousel-example-generic").on("slide.bs.carousel", function(event) {
      let $hoder = $("#carousel-example-generic").find(".item"),
        $items = $(event.relatedTarget);
      let getIndex = $hoder.index($items);
      if (getIndex) {
        $("#hp-indicators .active").removeClass("active");
        $("#hp-indicators li")
          .eq(getIndex)
          .addClass("active");
      } else {
        $("#hp-indicators .active").removeClass("active");
        $("#hp-indicators li")
          .eq(0)
          .addClass("active");
      }
    });
    $("#hp-indicators li").click(function() {
      $("#hp-indicators .active").removeClass("active");
      if (!$(this).hasClass("active")) {
        $(this).addClass("active");
      }
    });
  },
  methods: {
    scrollTo(ele, speed) {
      if (!speed) speed = 300;
      if (!ele) {
        $("html,body").animate({ scrollTop: 0 }, speed);
      } else {
        if (ele.length > 0)
          $("html,body").animate(
            { scrollTop: $(ele).offset().top - 80 },
            speed
          );
      }
      return false;
    }
  }
};
</script>

<style>
html {
  font-size: 13px !important;
}
.chunk1 {
  position: relative;
}
#navbar {
  color: #878787;
  position: absolute;
  top: 7rem;
  left: 0;
  line-height: 6rem;
  width: 100%;
  z-index: 1000;
  /* background: #fff; */
  /* box-shadow: 0 2px 4px rgba(0, 0, 0, 0.14);  */
}
#navbar span:hover {
  cursor: pointer;
  color: #38a0f6;
}
.chunk2 {
  position: relative;
  padding: 3rem 0;
  background-color: #4c4c4c;
}
.text1 {
  margin-top: 1rem;
  font-family: PingFang-SC-Bold;
  font-size: 1.7rem;
  font-weight: normal;
  font-stretch: normal;
  line-height: 3.3rem;
  letter-spacing: 0rem;
  color: #ffffff;
}

.text2 {
  margin-bottom: 1rem;
  font-family: PingFang-SC-Bold;
  font-size: 1.7rem;
  line-height: 3.3rem;
  color: #fedc91;
}
.botton {
  margin: 1rem;
  min-height: 4.6rem;
  border-radius: 3rem;
  border: solid 0.06rem #ffffff;
}
.num {
  font-family: PingFang-SC-Bold;
  font-size: 2rem;
  font-weight: normal;
  font-stretch: normal;
  line-height: 6rem;
  letter-spacing: 0rem;
  color: #ffffff;
}
.chunk3 {
  position: relative;
  padding: 6rem 0;
}
.title {
  font-family: PingFang-SC-Bold;
  font-size: 2.88rem;
  font-weight: normal;
  font-stretch: normal;
  line-height: 4rem;
  letter-spacing: 0rem;
  color: #000000;
  font-weight: bold;
  text-align: center;
  margin-bottom: 1.32rem;
}

.chunk3 .lable {
  min-height: 2.28rem;
  font-family: PingFang-SC-Bold;
  font-size: 1.8rem;
  font-weight: normal;
  font-stretch: normal;
  line-height: 2.28rem;
  letter-spacing: 0rem;
  color: #000000;
}
.chunk3 .synopsis {
  margin-top: 1rem;
  min-height: 9.12rem;
  font-family: PingFang-SC-Regular;
  font-size: 1.2rem;
  font-weight: normal;
  font-stretch: normal;
  line-height: 2.28rem;
  letter-spacing: 0rem;
  color: #4d4d4d;
}
.chunk4 {
  position: relative;
  padding: 6rem 0;
  min-height: 51.6rem;
  background-color: #f5f5f5;
}
.mac {
  width: 42rem;
  height: 33.6rem;
  margin: auto;
  background: url("../assets/mac.png") center no-repeat;
  background-size: 100% 100%;
}
.carousel-inner {
  position: relative;
  width: 94% !important;
  margin: 0% 3%;
  overflow: hidden;
}
.carousel-inner > .item > img {
  line-height: 1;
  width: 100%;
  margin-top: 4%;
  /* margin: 4% 3%; */
}

#hp-indicators li {
  padding-right: 3rem;
  text-align: center;
  list-style-type: none;
  width: 21.6rem;
  margin: auto;
  line-height: 4.2rem;
  font-family: PingFang-SC-Regular;
  font-size: 1.8rem;
  font-weight: normal;
  font-stretch: normal;
  letter-spacing: 0rem;
  color: #000000;
}
#hp-indicators li.active {
  background: url(../assets/current.png) center no-repeat;
  background-size: 100% 100%;
  color: #ffffff;
}
#hp-indicators li:not(.active):hover {
  background: url(../assets/current.png) center no-repeat;
  background-size: 100% 100%;
  color: #ffffff;
  -webkit-filter: opacity(50%);
  filter: opacity(50%);
}

.chunk5 {
  position: relative;
  padding: 6rem 0;
  min-height: 43.2rem;
  font-family: PingFang-SC-Regular;
  font-size: 1.44rem;
}
.line {
  width: 50%;
  border-right: 0.1rem solid #d7d7d7;
  min-height: 15rem;
}
.chunk5 .lable {
  /* width: 42rem; */
  margin-bottom: 1.8rem;
  /* height: 2.52rem; */
  font-size: 1.8rem;
  color: #000000;
}
.chunk5 .tel {
  height: 4.74rem;
  font-family: Impact;
  font-size: 3.84rem;
  letter-spacing: 0rem;
  color: #1f7dbc;
}
.introduce {
  min-height: 17.64rem;
  /* width: 29.58rem; */
  margin: auto;
  line-height: 2.7rem;
}
.introduce img {
  margin-right: 1rem;
}
.footer {
  padding: 2.34rem;
  background-color: #1f7dbc;
  font-family: PingFang-SC-Regular;
  font-size: 1.44rem;
  color: #ffffff;
  text-align: center;
  line-height: 2;
}
@media (max-width: 768px) {
  .chunk3 .lable {
    margin-top: 1rem;
    text-align: center;
  }
  .chunk3 .synopsis {
    font-size: 1.4rem;
    text-align: center;
  }
}
@media (max-width: 500px) {
  .mac {
    width: 29rem;
    height: 23rem;
  }
  html {
    font-size: 12px !important;
  }
}
@media (max-width: 374px) {
  .mac {
    width: 24rem;
    height: 19rem;
  }
  html {
    font-size: 10px !important;
  }
}
</style>
