<template>
  <div class="container">
    <!--<div id="parent">

      <div id="child"> asfasdasdasdas</div>
    </div>-->

    <div class="main-btn money"><span>图标</span>
      <p>充值</p>
      <a href="###" class="cover"></a>
    </div>
    <div class="main-btn service"><span>图标</span>
      <p>客服</p>
      <a href="###" class="cover"></a>
    </div>
    <div class="period">
      <p>距离222222期截止</p>
      <p class="main-btn">02分19秒</p>
    </div>
  </div>
</template>
<style>
  .cover {
    width: 100%;
    height: 100%;
    position: absolute;
    background: #fff;
    opacity: 0;
    top:0;
    left: 0;
  }

  .container {
    text-align: center;
    min-width: 25rem;
  }

  .money {
    float: left;
    background: green;
    box-shadow: 0 .2rem .0625rem darkgreen;
  }

  .main-btn {
    color: #fff;
    padding: .2rem 1.5rem .5rem 1.5rem;
    font-size: 1rem;
    margin: 0 1rem;
    border-radius: .2rem;
    position: relative;
  }

  .service {
    float: right;
    background: blue;
    box-shadow: 0 .2rem .0625rem darkblue;
  }

  .period {
    overflow: hidden;
    padding-bottom: .2rem;
  }

  .period .main-btn {
    background: red;
    box-shadow: 0 .2rem .0625rem darkred;
  }
</style>
