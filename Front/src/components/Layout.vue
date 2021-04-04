<template>
  <div class="homeWarp">
    <el-container style="height:100%;" direction="vertical">
      <el-header>
        <el-menu theme="dark" :default-active="activeIndex"
          class="el-menu-demo" mode="horizontal" @select="handleSelect">
            <el-menu-item index="1">首页</el-menu-item>
            <el-menu-item index="2">组织信息</el-menu-item>
            <el-menu-item index="3">项目信息</el-menu-item>
            <el-menu-item index="4">关于我们</el-menu-item>
            <el-menu-item index="5">登录</el-menu-item>
        </el-menu>
      </el-header>
      <el-main>
        <div class="demo-image__placeholder">
          <div class="block">
            <el-image
            style="width: 100%; height: 100%; margin:0px 0px 0px 0px;"
            :src="require('@/assets/charity.png')"></el-image>
            <br><br><br><br><br><br><br>
            <font style="font-size: 40px; font-weight: bold; font-family: 宋体;">区块链方案</font>
            &nbsp;&nbsp;
            <font style="font-size: 38px; font-weight: bold; font-family: 宋体; color: #409EFF;">推动慈善信息透明</font>
            <hr align=center width=300 color=#55557f SIZE=5>
            <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安作为区块链技术的践行者，突破常规公益模式，并与区块链技术完美契合。不断赋能慈善事业创新发展。</font>
            <br>
            <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界</font>
            <br>
            <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">去赋能更多被忽略群体的责任。币安慈善落地中国，希望能够通过行动和最佳实践，引领区块链行业思考并探</font>
            <br>
            <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">索社会价值。”由于区块链技术独有的透明可追溯性，以及不可逆改性。相信未来公益事业在区块链领域发挥</font>
            <br>
            <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">的空间会更大，与此同时，币安慈善也将一直在路上，在“炎热的夏季给予清爽，在寒冷的冬季送上温暖。”</font>
            <br><br><br><br><br><br><br>
            <div class="header">
              <div class="header-blank">
              </div>
              <div class="header-left">
                <img src="@/assets/btb.jpg" >
                <br><br><br>
                <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界</font>
              </div>
              <div class="header-center">
                <img src="@/assets/btb.jpg" >
                <br><br><br>
                <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界</font>
              </div>
              <div class="header-center">
                <img src="@/assets/btb.jpg" >
                <br><br><br>
                <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界</font>
              </div>
              <div class="header-right">
                <img src="@/assets/btb.jpg">
                <br><br><br>
                <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界</font>
              </div>
              <div class="header-blank">
              </div>
            </div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
            <div class="header2">
              <div class="header-blank2">
              </div>
              <div class="header-center-characters">
                <font style="font-size: 30px; font-weight: bold; font-family: 宋体;">区块链方案</font>
                &nbsp;&nbsp;
                <font style="font-size: 30px; font-weight: bold; font-family: 宋体; color: #409EFF;">推动慈善信息透明</font>
                <hr align=center width=300 color=#55557f SIZE=5>
                <font style="font-size: 18px; font-weight: bold; font-family: 宋体; color: #000000;">币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界币安慈善全球负责人HelenHai说过：”技术是没有边界的，区块链作为最前沿的科技，就天然承载着打破边界</font>
              </div>
              <div class="header-blank2">
              </div>
            </div>
            <br><br><br><br><br><br><br><br><br>
            <div class="header">
              <div class="header-blank">
              </div>
              <div class="frame">
                <img src="@/assets/btb.jpg">
                <font class="subtitle" style="font-size: 20px; font-weight: bold; font-family: 宋体; float: left;">区块链</font>
                <hr class="underline" align=left width=60 color=#00aaff SIZE=5>
                <p class="paragraph" style="font-size: 15px; font-weight: bold; font-family: 宋体; color: #000000;">承载着打破边界承载着打破边界承载着打破边界承载着着打破边界承载着打破边界承载</p>
              </div>
              <div class="frame">
                <img src="@/assets/btb.jpg">
                <font class="subtitle" style="font-size: 20px; font-weight: bold; font-family: 宋体; float: left;">区块链</font>
                <hr class="underline" align=left width=60 color=#00aaff SIZE=5>
                <p class="paragraph" style="font-size: 15px; font-weight: bold; font-family: 宋体; color: #000000;">承载着打破边界承载着打破边界承载着打破边界承载着着打破边界承载着打破边界承载</p>
              </div>
              <div class="frame">
                <img src="@/assets/btb.jpg">
                <font class="subtitle" style="font-size: 20px; font-weight: bold; font-family: 宋体; float: left;">区块链</font>
                <hr class="underline" align=left width=60 color=#00aaff SIZE=5>
                <p class="paragraph" style="font-size: 15px; font-weight: bold; font-family: 宋体; color: #000000;">承载着打破边界承载着打破边界承载着打破边界承载着着打破边界承载着打破边界承载</p>
              </div>
              <div class="header-blank">
              </div>
            </div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
            <div class="header">
              <div class="header-blank">
              </div>
              <div class="frame">
                <img src="@/assets/btb.jpg">
                <font class="subtitle" style="font-size: 20px; font-weight: bold; font-family: 宋体; float: left;">区块链</font>
                <hr class="underline" align=left width=60 color=#00aaff SIZE=5>
                <p class="paragraph" style="font-size: 15px; font-weight: bold; font-family: 宋体; color: #000000;">承载着打破边界承载着打破边界承载着打破边界承载着着打破边界承载着打破边界承载</p>
              </div>
              <div class="frame">
                <img src="@/assets/btb.jpg">
                <font class="subtitle" style="font-size: 20px; font-weight: bold; font-family: 宋体; float: left;">区块链</font>
                <hr class="underline" align=left width=60 color=#00aaff SIZE=5>
                <p class="paragraph" style="font-size: 15px; font-weight: bold; font-family: 宋体; color: #000000;">承载着打破边界承载着打破边界承载着打破边界承载着着打破边界承载着打破边界承载</p>
              </div>
              <div class="frame">
                <img src="@/assets/btb.jpg">
                <font class="subtitle" style="font-size: 20px; font-weight: bold; font-family: 宋体; float: left;">区块链</font>
                <hr class="underline" align=left width=60 color=#00aaff SIZE=5>
                <p class="paragraph" style="font-size: 15px; font-weight: bold; font-family: 宋体; color: #000000;">承载着打破边界承载着打破边界承载着打破边界承载着着打破边界承载着打破边界承载</p>
              </div>
              <div class="header-blank">
              </div>
            </div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
          </div>
        </div>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'Layout',
  data () {
    return {
      activeIndex: '1',
      activeIndex2: '1',
      src: '../assets/charity.png'
    }
  },
  methods: {
    handleSelect (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>

<style type="text/css">
.homeWarp {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.el-main {
  padding: 0px 0px 0px 0px;
}
.el-header, .el-footer {
  padding: 0;
  background-color: #B3C0D1;
  color: #333;
  text-align: center;
  line-height: 60px;
}
.header {
  width: 100%;
  height: 84px;
  display: flex;
  justify-content: space-between;
}
.header2 {
  width: 100%;
  height: 100px;
  display: flex;
  justify-content: space-between;
}
.header-left, .header-center, .header-right {
  width: 300px;
  height: 270px;
  padding-top: 11px;
}
.header-blank {
  width: 10px;
  height: 20px;
  padding-top: 11px;
}
.header-blank2 {
  width: 1px;
  height: 1px;
  padding-top: 11px;
}
.header-center-characters {
  width: 700px;
  height: 270px;
  padding-top: 11px;
}
.header-left img, .header-center img, .header-right img {
  width: 100%;
  height: 100%;
}
.frame {
  width: 380px;
  height: 250px;
  padding-top: 11px;
  border-width: 5px;
  border-style: solid;
  border-color: #409EFF;
}
.frame img {
  width: 120px;
  height: 120px;
  float: left;
  margin: 2px 330px 0px 15px;
}
.subtitle {
  margin: 10px 300px 10px 15px;
}
.underline {
  margin: 10px 150px 10px 15px;
}
.paragraph {
  margin: 5px 15px 0px 12px;
  display : inline-block;
  text-align : left;
}
</style>
