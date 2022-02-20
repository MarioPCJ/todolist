<template>
  <body>
  <div class="home">
    <div class="destaqueLight">
      <h1 class="title">TODO</h1>
    <a href="/about" class="btnDark"></a>
    </div>
    
  </div>
  </body>
</template>
<script>

</script>

<style>
 body {
  background-color: hsl(0, 0%, 98%);
}

.destaqueLight{
  background-image: url('../assets/images/bg-desktop-light.jpg');
  background-position: center;
  height: 300px;
  background-repeat: no-repeat;
   
}

.btnDark{
  background:url('../assets/images/icon-moon.svg') no-repeat center right;
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
