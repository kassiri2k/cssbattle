<!-- 
I set a container or a wrapper that contains the 4 squares and place them at the extremities with top,right,left...
I use the position absolute to set all squares at  the same place at the beginning (0,0) of the container

 -->
<div class="container">
  <div class="box topleft"></div>
  <div class="box topright"></div>
  <div class="box bottomright"></div>
  <div class="box bottomleft"></div>
</div>

<style>
  .box{
    height:50px;
    width:50px;
    background-color:#fdc57b;
    position: absolute;
  }
  .container{
    height:200px;
    width:300px;
    position: relative;
    top:50px;
    left:50px;
  }
  .topright{
    right:0;
  }
  .bottomleft{
    bottom:0
  }
  .bottomright{
    bottom:0;
    right:0;
  }
  
body{
  background-color:#62374e;
  margin:0;
}  
</style>