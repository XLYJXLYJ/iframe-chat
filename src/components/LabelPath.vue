<template>
  <div class="label-contain">
      <h1>标签</h1>
      <ul class="contain-ul">
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
          <li>2222</li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'labelPath',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.label-contain{
  position: relative;
  width: 100%;
  height: 100%;
  font-family: '微软雅黑';
  h1{
    font-size: 20px;
    width: 100%;
    height: 10%;
    font-family: '微软雅黑';
    font-weight: bold;
    margin-bottom: 20px;
    position: absolute;
    top: 0px;
    left: 0px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 10px;
    border-radius: 15px;
    box-shadow:0px 3px 9px 0px rgba(82, 82, 82, 0.35);
    background: #fff;
  }
  .contain-ul{
    display: flex;
    justify-content:space-around;
    flex-wrap:wrap;
    overflow: auto;
    width: 100%;
    height: 70%;
    position: relative;
    top: 25%;
    li{
      padding: 20px;
      padding-top: 10px;
      padding-bottom: 10px;
      border-radius: 10px;
      margin-bottom: 20px;
      background: #428dc7;
      color: #fff;
    }
  }
  .contain-ul::-webkit-scrollbar {/*滚动条整体样式*/
    width: 10px;     /*高宽分别对应横竖滚动条的尺寸*/
    height: 271px;
  }
  .contain-ul::-webkit-scrollbar-thumb {/*滚动条里面小方块*/
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 5px #fff;
    background: #fff;
  }
  .contain-ul::-webkit-scrollbar-track {/*滚动条里面轨道*/
    -webkit-box-shadow: inset 0 0 5px #fff;
    border-radius: 10px;
    background: #fff;
  }
}
</style>
