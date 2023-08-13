<!-- put the elements left top... it is more an inefficient solution  -->
<div class="one bot"></div>
<div class="two"></div>
<div class="three bot"></div>

<style>
  
  body{
    background: #62306D;
   
  }
  .one{
    height:100px;
    width:100px;
    position:absolute;
    top:150px;
    left:50px;
    
  }
  
  .two{
      height:100px;
    width:100px;
    background:#F7EC7D;
     border-top-left-radius:50px;
    border-top-right-radius:50px;
    position:absolute;
    top:50px;
    left:150px;
  }
  
  .three{
    
     height:100px;
    width:100px;
    position:absolute;
      top:150px;
    left:250px;
  }
  .bot{
    background-color:#F7EC7D;
    border-bottom-left-radius:50px;
    border-bottom-right-radius:50px;
  }

</style>
