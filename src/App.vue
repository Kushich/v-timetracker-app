<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
};
</script>

<style>
@import url('../static/fonts/iconic/css/material-design-iconic-font.min.css'); 
@import url('../static/fonts/font-awesome-4.7.0/css/font-awesome.min.css'); 
@import url('../static/css/util.css'); 
  body {
    background: rgb(255,128,0);
    background: linear-gradient(90deg, rgba(255,128,0,0.4962359943977591) 0%, rgba(236,255,0,0.4990371148459384) 35%, rgba(236,255,0,0.5018382352941176) 65%, rgba(255,128,0,0.5970763305322129) 100%);
  }
  #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #333;
  margin-top: 60px;
}

label {
  font-size: 1.5em;
}

/* responsive */
@media (max-width: 576px) {
  #app {
    margin-top: 20px;
  }
}
</style>
