<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>

<style>
*{
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
  background: rgb(9,31,61);
  background: linear-gradient(6deg,  rgb(3, 26, 58) 0%, rgba(9,31,61,1) 20%, rgb(43, 83, 114) 100%);  
  height: 500px;
  width: 380px;
  padding: 30px;
}
</style>
