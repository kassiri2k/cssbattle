<div>
<div class= "center">
    <div class="bar one"></div>
    <div class="bar two"></div>
    <div class="bar three"></div>
    <div class="bar four"></div>
    <div class="bar five"></div>
    <div class="bar six"></div>
    <div class="bar seven"></div>
</div>
  <div class= "stick"></div>
</div>


<style>
  .two{
    left:20px;
  }
    .three{
    left:40px;
  }
    .four{
    left:60px;
  }
    .five{
    left:80px;
  }
    .six{
    left:100px;
  }
    .seven{
    left:120px;
  }
  .stick{
    height:110px;
    background-color: #060F55;
    position: absolute;
    width:20px;
    left: 190px;
    bottom:0;
  }
  .center{
    width:140px;
    height:200px;
    background:linear-gradient(to bottom,#6592CF 50%,#060F55 50%);
    position: relative;
    border-radius: 0 0 100px 100px;
  }
  .bar:nth-child(odd){
    background-color:#060F55;
    height:110px;
    width:20px;
    position: absolute;
    border-radius:10px 10px 0 0;

  }
  .bar:nth-child(even){
    background-color:#6592CF;
    height:110px;
    width:20px;
    position: absolute;
    border-radius:0 0 10px 10px;
  }
  body{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color:#6592CF;
    margin:0;
  
  }
</style>