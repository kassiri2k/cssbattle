<!-- There is a problem with the border: when I googled it it says:
When an element is rotated, it can cause the element to exceed its original dimensions and potentially reveal the background of the parent container. The solution will be to add an extra wrapper. It will take me more lines but it will solve the problems :/ -->
<div class ="band"></div>
<div class= "center">
  <div class= "middle"></div>
</div>
<style>
.center{
  height:250px;
  width:250px;
  position: absolute;
  background-color: #4CAAB3;
  transform:rotate(45deg);
  border: 50px solid #222730;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
}
  .middle {
    height:50px;
    width:50px;
    background-color:#393E46;
    border-radius:50%;
  }
.band{
  background-color:#4CAAB3;
  height:150px;
  width:100%;
  position: relative;
}
  body{
    background-color:#222730;
    margin:0;
    display:flex;
    justify-content:center;
    align-items:center;
  }
</style>