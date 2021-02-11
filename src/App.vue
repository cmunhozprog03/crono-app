<template>
  <div id="app">
    <img src="./assets/cronometro.png" class="img" alt="">
    
    <a class="timer">00:00,00</a>

    <div class="areaBtn">
      <button class="botao">VAI</button>
      <button class="botao">LIMPAR</button>
    </div>
    
  </div>
</template>

<script>


export default {
  name: 'App',
  
}
</script>

<style>
  #app{
    display: flex;
    width: 100%;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .img{
    width: 450px;
    height: 450px;
    padding-top: 70px;
  }
  .timer{
    color: #ffffff;
    font-size: 70px;
    margin-top: -230px;
  }
  .areaBtn{
    margin-top: 155px;
    display: flex;
  }
  .botao{
    -webkit-user-select: none;
    -moz-user-select: none;
    width: 150px;
    background-color: #FFF;
    font-size: 20px;
    border:0;
    border-radius: 5px;
    text-align: center;
    margin-left: 15px;
    margin-right: 15px;
    padding: 6px;
    cursor:pointer;
  }
  .botao:hover{
    opacity: 0.7;
    transition: all 0.50s;
  }
</style>
