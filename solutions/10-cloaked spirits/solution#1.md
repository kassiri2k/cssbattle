<div class = "wrapper">
  <div class="bar left">
    <div class= "form extremity  big">
      <div class= "pform small ext"></div>
    </div>
  </div>
  <div class= "bar middle">
        <div class= "form mid big">
      <div class="pform mi"></div>
    </div>
  </div>
  <div class=" bar right">
        <div class="form extremity big">
      <div class="pform small ext"></div>
    </div>
  </div>
</div>

<style>
  .extremity{
    background-color:#AA445F;
  }
  .form{
    height:100px;
    width:100px;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items: center;
    
  }
    .pform{
    height:60px;
    width:60px;
    border-radius:50%;
  }
  .bar{
    width:100px;
    background-color:#F7EC7D;
    bottom:0;
    border-radius: 50px 50px 0 0
  }
  .mid{
    background-color:#E38F66;
  }
  .left,.right{
    height:150px;
    position: relative;
    top:100px;
  }
  .ext{
    background-color:#E38F66;

  }
  .mi{
     background-color:#AA445F;
  }
  .wrapper{
    position: relative;
    height:250px;
    width:300px;
    left:42px;
    top:42;
    display: flex;
    justify-content: center;
  }
body{
  background-color:#62306D;

}
</style>