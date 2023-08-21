<!-- old solution -->

<div class="mid">
</div>
<div class="midc">
  <div class="o">
</div>
</div>

<div class="left">
</div>
<div class=" ex midc1">
    <div class="o1">
</div>
</div>

<div class="right">
</div>
<div class="ex midc2">
    <div class="o2">
</div>
</div>
<style>
  body{
    background-color:#62306D;
    margin:0 0 0 0;
  }
  .mid{
    background-color:#F7EC7D;
    height:280;
    width:100px;
    position:absolute;
    top:80;
    left:150;
    border-top-left-radius:20px;
    border-top-right-radius:20px;
  }
   .midc{
    background-color:#E38F66;
    height:100px;
    width:100px;
     border-radius:50%;
    position:absolute;
    top:50;
    left:150;
     display:flex;
     justify-content:center;
     align-items:center;
  }
  .o{
     height:60px;
    width:60px;
    background-color:#AA445F;
    border-radius:50%;
  }
  .left{
    background-color:#F7EC7D;
   height:100px;
    width:100px;
    position:absolute;
    top:200;
    left:50;
  }
   .right{
    background-color:#F7EC7D;
   height:100px;
    width:100px;
    position:absolute;
    top:200;
    left:250;
  }
  .midc1{
      background-color:#AA445F;
    height:100px;
    width:100px;
     border-radius:50%;
    position:absolute;
    top:150;
    left:250;
    z-index:1;
     display:flex;
     justify-content:center;
     align-items:center;
  }
   .o1{
     height:60px;
    width:60px;
    background-color:#E38F66;
    border-radius:50%;
  }
    .midc2{
      background-color:#AA445F;
    height:100px;
    width:100px;
     border-radius:50%;
    position:absolute;
    top:150;
    left:50;
    z-index:1;
     display:flex;
     justify-content:center;
     align-items:center;
  }
   .o2{
     height:60px;
    width:60px;
    background-color:#E38F66;
    border-radius:50%;
  }
  
</style>