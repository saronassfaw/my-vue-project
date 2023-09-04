<template>
  <h1>CHARACTERS</h1>
<div class="pictures">

    <img src="./miless.png" class="miles">
    <p class="t1">Miles</p>

    <img src="./gwenn.png"  class="gwen"> 
    <p class="t1">Gwen</p>

    <img src="./pavi.png"  class="pavi">
    <p class="t3">Pavitir</p>

    <img src="./miguell.png"  class="miguel">
    
</div>


</template>

 <style scoped>
    h1{
    margin-top: 80px;
    font-family: Verdana, Geneva, Tahoma, sans-serif, bold;
    text-align: center;
  }

  #pictures{
    display: flex;
    flex-direction: row;
    align-items: center;

  }
  img.miles:hover p.t1{
    visibility: visible;
    opacity: 1;
  }
  p.t1{
    margin-left: 100px;
    margin-right: 15px;
    margin-bottom: 100px;
  }
  img{
    width: 18%;
    margin-left: 80px;
    margin-right: 15px;
    margin-top: 150px;
    margin-bottom: 200px;
    position: relative;
  }
  img:hover{
    -webkit-filter: brightness(165%);
  }
  p{
    position: absolute;
    background: rgba(29, 106, 154, 0.72);
    color: #fff;
    visibility: hidden;
    opacity: 0;
    transition: opacity .2s, visibility .2s;
  }

   </style>