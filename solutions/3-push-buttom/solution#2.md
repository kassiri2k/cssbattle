<!-- I use a container and put the circle in it. I do not use the propery absolute to put the rectangle in the background
I use instead a property border , box-sizing and make the inner transparent -->
<div class="container">
  <div class="circle big"></div>
  <div class="circle small"></div>
</div>
<style>
  .container{
    height:150px;
    width:300px;
    background-color:#243D83;
    margin: 75px auto;
    position: relative;
  }
  .circle{
    border-radius:50%;
  }
  .big{
    height:250px;
    width:250px;
    background-color: red;
    position: absolute;
    top:-50px;
    left:25px;
    border: 50px solid #6592CF;
    box-sizing:border-box;
    background: transparent;
  }
  .small{
    height:50px;
    width:50px;
    position: absolute;
    background-color:#EEB850;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%)
  }
body{
  background-color:#6592CF;
  margin:0;
}  
</style>