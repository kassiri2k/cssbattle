<div class= "wrapper">
  <div class="box left"></div>
   <div class="box right"></div>
</div>
<style>
  .wrapper{
    width:160px;
    height:160px;
    position:relative;    
  }
  .box{
    height:160px;
    width:80px;
    background-color:#F7EC7D;
  }
  .left{
    border-top-left-radius:100px;
    border-bottom-right-radius:50px;
  }
  .right{
    border-top-right-radius:100px;
    top:0;
    position: absolute;
    right:0;
    border-bottom-left-radius:50px;
  }
body{
  background-color:#62306D;
  margin:0;
  display:flex;
  justify-content:center;
  align-items:center;
}
</style>
