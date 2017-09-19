<template>
  <div>
  <mu-flexbox class="mt8">
      <mu-flexbox-item  class="flex-demo">
      <img src="../../assets/1.png" class="img1"/>
        <p>领券</p>
      </mu-flexbox-item>
      <mu-flexbox-item class="flex-demo">
       <img src="../../assets/2.png" class="img2"/>
        <p>社区互动</p>
      </mu-flexbox-item>
      <mu-flexbox-item class="flex-demo">
       <img src="../../assets/3.png" class="img3"/>
        <p>我的收藏</p>
      </mu-flexbox-item>
       <mu-flexbox-item class="flex-demo">
        <img src="../../assets/4.png" class="img4"/>
        <p>新品试用</p>
      </mu-flexbox-item>
    </mu-flexbox>

    <mu-flexbox class="mt8">
      <mu-flexbox-item class="flex-demo">
       <img src="../../assets/5.png" class="img5"/>
        <p>私人定制</p>
      </mu-flexbox-item>
      <mu-flexbox-item class="flex-demo">
       <img src="../../assets/6.png" class="img6"/>
        <p>在线客服</p>
      </mu-flexbox-item>
      <mu-flexbox-item class="flex-demo">
       <img src="../../assets/7.png" class="img7"/>
        <p>物流查询</p>
      </mu-flexbox-item>
       <mu-flexbox-item class="flex-demo">
        <img src="../../assets/8.png" class="img8"/>
        <p>乐豆抽奖</p>
      </mu-flexbox-item>
    </mu-flexbox>

  </div>
</template>
<script>
export default{
  name:'flex'
  
}
</script>


<style lang="css">
.mt8{
  margin:0.08rem;
 
}
.flex-demo {
  height:1rem;
  background-color: #fff;
  text-align: center;
  line-height: 0.08rem;
}
.img1,.img2,.img3,.img4,.img5,.img6,.img7,.img8{
  width:0.6rem;
  height:0.6rem;
}
</style>



