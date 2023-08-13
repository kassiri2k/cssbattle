<!-- put the elements in a wrapper and use a top left for the position -->
<div class="wrapper">
<div class="box left"></div>
<div class="box middle"></div>
<div class="box right"></div>
</div>

<style>
  .wrapper{
    height:200px;
    width:300px;
    position: relative;
    margin: 50px auto;
  }
.box{
  height:100px;
  width:100px;
  background-color:#F7EC7D;
  position: absolute;
}
  .left{
    bottom:0;
    border-radius:0 0 50% 50%
  }
  .right{
   right:0;
    bottom:0;
    border-radius:0 0 50% 50%
  }
  .middle{
    left:50%;
    transform: translate(-50%);
    border-radius:50% 50% 0 0;
  }
body{
  background:#62306D;
  margin:0;
}
  
</style>