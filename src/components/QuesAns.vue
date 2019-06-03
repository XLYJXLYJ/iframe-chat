<template>
  <div class="ques-contain">
    <h1 class="title">机器人答案</h1>
    <ul class="ques-ul">
      <li>
        <p class="q-title">你好</p>
        <p class="q-answeer">您好，我是企保保险客服，很高兴为你服务！</p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
      <li>
        <p class="q-title">推荐</p>
        <p class="q-answeer">请问，您需要哪类保险产品？健康险还是旅游意外险？请您留下联系方式，我们将安排保险专员为您服务。</p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
      <li>
        <p class="q-title">介绍疾病保险</p>
        <p class="q-answeer">疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
        </p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
      <li>
        <p class="q-title">你是</p>
        <p class="q-answeer">你好！我是Aimi，欢迎咨询。</p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
            <li>
        <p class="q-title">你好</p>
        <p class="q-answeer">您好，我是企保保险客服，很高兴为你服务！</p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
      <li>
        <p class="q-title">推荐</p>
        <p class="q-answeer">请问，您需要哪类保险产品？健康险还是旅游意外险？请您留下联系方式，我们将安排保险专员为您服务。</p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
      <li>
        <p class="q-title">介绍疾病保险</p>
        <p class="q-answeer">疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
          疾病保险的简介：指当被保险人患保单指定的重大疾病确诊后，保险公司按合同约定定额支付保险金的保险
        </p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
      <li>
        <p class="q-title">你是</p>
        <p class="q-answeer">你好！我是Aimi，欢迎咨询。</p>
        <!-- <p class="img-p" title="收起详情"><img src="../assets/img/s.png"></p> -->
        <p class="img-p" title="展开详情"><img src="../assets/img/z.png"></p>
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'quesAns',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
  .ques-contain{
    display: flex;
    height: 100%;
    width: 100%;
    flex-direction:column;
    .title{
      width: 100%;
      height: auto;
      font-size: 24px;
      font-family: '微软雅黑';
      font-weight: bold;
      margin-top: 20px;
      margin-bottom: 20px;
      padding-top: 10px;
      padding-bottom: 35px;
      border-radius: 15px;
      text-align: center;
      margin: 0 auto;
    }
    .ques-ul{
      display: flex;
      width: 100%;
      flex-direction:column;
      overflow: auto;
      li{
        margin-top: 20px;
        margin-bottom: 20px;
        padding: 20px;
        padding-bottom: 10px;
        border-radius: 35px;
        box-shadow:0px 3px 9px 0px rgba(82, 82, 82, 0.35);
        .q-title{
          font-size: 20px;
          font-family: '微软雅黑';
        }
        .q-answeer{
          font-size: 16px;
          font-family: '微软雅黑';
        }
        .img-p{
          display: flex;
          justify-content: center;
          img{
            width: 30px;
            height: 30px;
            margin-top: 10px;
            cursor: pointer;
          }
        }
        .img-p:hover{
          cursor: pointer;
        }
      }
    }
    .ques-ul::-webkit-scrollbar {/*滚动条整体样式*/
      width: 10px;     /*高宽分别对应横竖滚动条的尺寸*/
      height: 271px;
    }
    .ques-ul::-webkit-scrollbar-thumb {/*滚动条里面小方块*/
      border-radius: 10px;
      -webkit-box-shadow: inset 0 0 5px #428dc7;
      background: #428dc7;
    }
    .ques-ul::-webkit-scrollbar-track {/*滚动条里面轨道*/
      -webkit-box-shadow: inset 0 0 5px #428dc7;
      border-radius: 10px;
      background: white
    }
  }
</style>
