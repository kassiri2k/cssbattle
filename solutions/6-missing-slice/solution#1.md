<div class="wrapper">
  <div class="box one"></div>
  <div class="box two"></div>
  <div class="box three"></div>
</div>

<style>
  .wrapper{
    height:200px;
    width:200px;
    position: relative;
    background: transparent;
    left: 100px;
    top: 50px;
    
  }
  body{
    background-color:#E3516E;
    margin: 0;
  }
  .box{
    position: absolute;
    height: 100px;
    width: 100px;
  }
  .one{
    background-color:#51B5A9;
    border-radius:100% 0 0 0 ;
  }
  .two{
    background-color:#FADE8B;
    right:0;
    border-radius:0 100%  0 0 ;
  }
  .three{
    background-color:#F7F3D7;
    bottom:0;
    border-radius:0 0 0 100%;
  }
  
</style>