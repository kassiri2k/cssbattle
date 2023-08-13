<!-- 
I use the flex display to put the squares at the extremities(space between)
Then use the margin to adjust the right and left sides of the box

-->
<div>
  <div class="tp">
    <div class="box left"></div>
    <div class="box right"></div>
  </div>
    <div class="bt">
    <div class="box left"></div>
    <div class="box right"></div>
  </div>
  
</div>

<style>
  .tp,.bt{
    display: flex;
    justify-content: space-between;
    width:300px;
    position: relative;
  }
  .bt{
    top: 150px;
    left:50px;;
  }
  .tp{
    top: 50px;
    left: 50px;
  }
  .box{
    background-color:#fdc57b;
    height:50px;
    width: 50px;
  }
body{
  background-color:#62374e;
  margin:0;
}
  
</style>