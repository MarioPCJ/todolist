<template>
  <body>
  <div class="about">
    <div class="destaqueDark">
      <h1 class="title">TODO</h1>
    <a href="/" class="btnLight"></a>
    </div>
    
  </div>
  </body>
</template>
<style>
body{
  background-color: hsl(235, 21%, 11%);
}

.destaqueDark{
  background-image: url('../assets/images/bg-desktop-dark.jpg');
  background-position: center;
  height: 300px;
  background-repeat: no-repeat;
   
}

.btnLight{
  background:url('../assets/images/icon-sun.svg') no-repeat center right;
  background-size: 100%;
  position:absolute;
   top:10%;
    left:65%;
    width: 20px;
    height: 40px;
   }
  .title{
    position:absolute;
   top:10%;
    left: 35%;
    color: azure;
    font-family: 'Josefin Sans', sans-serif;
    font-weight: 700;
    letter-spacing: .6rem;
    
  }
</style>
