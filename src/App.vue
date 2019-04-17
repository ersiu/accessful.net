<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>

  .btn-secondary,
  .btn-secondary:hover,
  .btn-secondary:focus {
    color: #333;
    text-shadow: none;
    /* Prevent inheritance from `body` */
    background-color: #fff;
    border: .05rem solid #fff;
  }
  
  @font-face {
    font-family: 'Alba';
    src: url('assets/fonts/ALBA.TTF');
  }
  
  .bd-placeholder-img {
    font-size: 1.125rem;
    text-anchor: middle;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
  }
  
  a,
  a:focus,
  a:hover {
    color: #fff;
  }
</style>

