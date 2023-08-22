<!-- 99.9% matching fix the margin or ... -->
<div class = "wrapper">
  <div class = "box left"></div>
  <div class = "middle">
  <div class = "small"></div>
</div>
  <div class = "box right"></div>
</div>

<style>

  .small{
    height:50px;
    width:50px;
    background-color:#84271C;
    border-radius:50%;
  }
  .wrapper{
    display: flex;
    height:140px;
    width: 345px;
    align-items: center;
    border:solid;
    position:relative;
    left:3px;
    
  }
  .middle{
  height:100px;
  width:100px;
  border-radius:50%;
  border:20px solid #ECA03D;
  display:flex;
  justify-content:center;
  align-items:center;
    position:relative;
    
    
    
  }
  .box{
    height:100px;
    width:100px;
    position: relative;
    box-sizing:border-box;
    border: 20px solid  #ECA03D;
    border-radius: 50%;
    border-top: 20px solid transparent;
    border-left: 20px solid transparent;
    transform:rotate(45deg);
    

  }
  .left{
    top:0px;
    left: 18px;
    
  }
  .right{
transform:rotate(225deg);
    bottom:2px;
    right:20px;
  }
  body{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color:#191210;
    
  }
</style>