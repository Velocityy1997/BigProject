<template>
  <div class="top">
    <div class="topcontent">
      <div class="topcontain">
        <div class="topcontain1">
          <a href="/shouye1">网校首页</a>
        </div>
        <div class="topcontain2">
          <a href>教师资格证公示</a>
        </div>
        <div class="topcontain3">
          <a href>客户端下载</a>
        </div>
        <div class="topcontain4">
          <a href="/myorder">我的订单</a>
        </div>
        <div class="topcontain5">
          <a href="/setup">设置</a>
        </div>
        <div class="topcontain6">
          <a href>用户名</a>
          <img src="../assets/arrow.png" alt />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "top"
};
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
}
.top {
  width: 100%;
  height: 30px;
  background-color: #323534;
}
.topcontent {
  width: 1200px;
  height: 30px;
  margin: auto;
  background-color: #323534;
}
.topcontain {
  width: 490px;
  height: 30px;
  float: right;
  background-color: #323534;
}
.topcontain1 {
  width: 77px;
  height: 16px;
  margin-top: 7px;
  float: left;
  text-align: center;
  line-height: 16px;
  font-size: 12px;
  color: #b2ae9b;
  border-right: 1px solid #b2ae9b;
  cursor: pointer;
}
.topcontain1 a,
.topcontain2 a,
.topcontain3 a,
.topcontain4 a,
.topcontain5 a,
.topcontain6 a {
  color: #ccc;
  text-decoration: none;
}
.topcontain1 a:hover,
.topcontain2 a:hover,
.topcontain3 a:hover,
.topcontain4 a:hover,
.topcontain5 a:hover,
.topcontain6 a:hover {
  color: blue;
}

.topcontain2 {
  width: 113px;
  height: 16px;
  float: left;
  margin-top: 7px;
  float: left;
  text-align: center;
  line-height: 16px;
  font-size: 12px;
  color: #b2ae9b;
  cursor: pointer;
  border-right: 1px solid #b2ae9b;
}
.topcontain3 {
  width: 91px;
  height: 16px;
  float: left;
  margin-top: 7px;
  float: left;
  text-align: center;
  line-height: 16px;
  font-size: 12px;
  color: #b2ae9b;
  cursor: pointer;
  border-right: 1px solid #b2ae9b;
}
.topcontain4 {
  width: 79px;
  height: 16px;
  float: left;
  margin-top: 7px;
  float: left;
  text-align: center;
  line-height: 16px;
  font-size: 12px;
  color: #b2ae9b;
  cursor: pointer;
  border-right: 1px solid #b2ae9b;
}
.topcontain5 {
  width: 55px;
  height: 16px;
  float: left;
  margin-top: 7px;
  float: left;
  text-align: center;
  line-height: 16px;
  font-size: 12px;
  color: #b2ae9b;
  cursor: pointer;
  border-right: 1px solid #b2ae9b;
}
.topcontain6 {
  width: 61px;
  height: 16px;
  float: left;
  margin-top: 7px;
  float: left;
  text-align: center;
  line-height: 16px;
  font-size: 12px;
  cursor: pointer;
  color: #b2ae9b;
}
.topcontain .topcontain6 img {
  width: 12px;
  height: 13px;
}
</style>
