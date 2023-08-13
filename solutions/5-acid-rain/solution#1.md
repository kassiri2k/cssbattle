<div class ="wrapper">
  <div class="box right sc "></div>
  <div class="box middle sf"></div>
  <div class="box left sc sf"></div>
</div>

<style>
  .box{
    position: absolute;
    height:120px;
    width:120px;
    background-color:#F3AC3C;
  }
  .sc{
    background-color:#F3AC3C;
  }
  .sf{
    border-radius: 50% 0 50% 50%;
  }
  .right{
    border-radius: 50%;
    right:30
  }
    .left{
    left:30;
    bottom:0;
  }
    .middle{
    background-color: #998235;
    left:90px;
    top:60px;
  }
  .wrapper{
    height:240px;
    width:300px;
    position: relative;
    margin:30px auto;
  }
  body{
    background-color:#0B2429;
    margin:0;
  }
</style>