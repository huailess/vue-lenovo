<template>
<div class="demo-grid">
 
  <mu-row gutter>
   
    <mu-col width="33" tablet="33" desktop="33"><img src="../../assets/a1.jpg"/></mu-col>
    <mu-col width="33" tablet="33" desktop="33"><img src="../../assets/a2.jpg"/></mu-col>
    <mu-col width="33" tablet="33" desktop="33"><img src="../../assets/a3.jpg"/></mu-col>
    <mu-col><img src="../../assets/4.jpg"/></mu-col>
  </mu-row>
</div>
</template>
<script>
export default{
  name:"lvXing"
}
</script>

<style lang="css">
.demo-grid{
  margin-top:8px;
}
.demo-grid div[class*="col-"] {
  display:fixed;
  background: #fff;
  text-align: center;
  color: #000;
  padding: 5px;
  margin-bottom: 8px;
}
</style>