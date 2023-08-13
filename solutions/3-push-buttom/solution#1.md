<!-- I use the position absolute to put the rectangle in the background
Then put the small circle in the center of the middle and so on -->
<div class="big">
  <div class="middle">
    <div class="small"></div>
  </div>
</div>
<div class="rect">
</div>
<style>
  .big {
    height: 250px;
    width:250px;
    border-radius:50%;
    background-color:#6592CF;
    position: absolute;
    margin-left:25px;
    margin-top:-50px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .middle{
    background-color:#243D83;
    height:150px;
    width:150px;
    border-radius:50%;
        display: flex;
    justify-content: center;
    align-items: center;
  }
  .small{
    background-color:#EEB850;
    height:50px;
    width:50px;
    border-radius:50%;
  }
  .rect{
    width:300px;
    height:150px;
    background-color:#243D83;
  }
  body{
    background-color:#6592CF;
    margin:75px 0 0 50px;;
  }
</style>