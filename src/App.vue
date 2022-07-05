<template>
<div>
  <h3>{{info}}</h3>
  <a href="https://youku.com/" class="youku">优酷</a>
  <h3>{{info}}</h3>
  <a href="http://fjisu.top/" class="feijjisu">飞极速</a>
  <h3>{{info}}</h3>
  <a href="https://www.mgtv.com/" class="mangguo">芒果TV</a>
  <h3>{{info}}</h3>
  <a href="https://www.bilibili.com/" class="bili">哔哩哔哩</a>
  <h3>{{info}}</h3>
  <a href="https://www.abchina.com/cn/" class="byb">农业银行</a>
  <h3>{{info}}</h3>
  <a href="http://www.nbcb.com.cn/" class="nbb">宁波银行</a>
  <h3>{{info}}</h3>
  <a href="http://www.icbc.com.cn/icbc/" class="gsb">工商银行</a>
  <h3>{{info}}</h3>
  <a href="https://mybank.cn/" class="wsb">网商银行</a>
  <h3>{{info}}</h3>
  <a href="https://www.1688.com/" class="pt">1688平台</a>
  
</div>

</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; 
} 
.youku{
  color: rgb(111, 111, 5);
}
.feijisu{
  color: green;
}
.mangguo{
  color: orange;
}
.bili{
  color: pink;
}
.nyb{
  color:aquamarine;
}
.nbb{
  color:blue;
}
.gsb{
  color: red;
}
.wab{
  color: blueviolet;
}
.pt{
  color: orange;
}
</style>
