<template>
<div>
  <div class="home">
      <img alt="Vue logo" src="../assets/bg.jpg">
  </div>
  <h1>WE ORGANIZE</h1>
  </div>
</template>

<script>
  export default {
    name: 'Home',
  }
</script>

<style scoped>
    .home{
      
        height: 100%;
        display:flex;
        justify-content: center;
        align-items: center;
    }
    img{
      height: 50%;
      width:100%
      
    }
    h2{
      text-align: center;
      font-size:70px;
      color: dodgerblue;
      font-family: 'Times New Roman', Times, serif;
      font-style: oblique
    }
    h1{
      position:relative;
      margin-top: -25%;
      text-align: center;
      font-size: 80px;
      color:mediumblue
    }
</style>