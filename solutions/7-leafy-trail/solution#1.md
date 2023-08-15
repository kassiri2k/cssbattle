<div class = "wrapper">
  <div class="box one"></div>
  <div class="box two"></div>
  <div class="box three"></div>
</div>

<style>
  .wrapper{
    position: relative;
    height:150px;
    width:250px;
  }
  .box{
    height: 150px;
    width: 150px;
    position: absolute;
    border-top-left-radius:67%;
    border-bottom-right-radius:67%;
  }
  .one{
    background-color:#1A4341;
    
  }
  .two{
    background-color:#998235;
    left:50px;;
  }
  .three{
    background-color:#F3AC3C;
    right:0;
    
  }
body{
  background-color:#0B2429;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>