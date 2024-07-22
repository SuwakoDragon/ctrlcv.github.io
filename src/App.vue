<template>  
    <div id="app">  
      <h1>我的地图应用</h1>  
      <MyMapComponent />  
    </div>  
  </template>  
    
  <script>  
  // 引入MyMapComponent组件  
  import MyMapComponent from './components/MyMapComponent.vue';  
    
  export default {  
    name: 'App',  
    components: {  
      MyMapComponent // 注册MyMapComponent组件  
    }  
  }  
  </script>  
    

 <style>
  body{
      margin: 0;
      padding: 0;
      overflow: hidden;
  }
  #container{
      /* border: 1px solid black; */
      width: 100vw;
      height: 100vh;
  }
  #tooltip {
      position: absolute;
      z-index: 2;
      background: white;
      padding: 10px;
      border-radius: 5px;
      visibility: hidden;
  }

  #app {  
    font-family: Avenir, Helvetica, Arial, sans-serif;  
    text-align: center;  
    color: #2c3e50;  
    margin-top: -100px;  
    margin-left: -40px;
  }
</style>
 