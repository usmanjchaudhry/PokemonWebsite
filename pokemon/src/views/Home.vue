<template>
  <div class="home">


<div class="fvue">
  <img class="catch" src="https://www.freepnglogos.com/uploads/pokemon-logo-text-png-7.png">
</div>



<div class="fvue2">
  <img class="catch9" href ="about" src="https://www.pngkey.com/png/full/56-566109_pikachu-transparent-background-pokmon-pikachu.png">
</div>


<h1 class="text">Click me to view all pokemon</h1>

</div>

 

  </template>

  
  


<script>


export default {
  name: "Home",
  components: {
    
  },
};
</script>



<style scoped>

.fvue {
  margin-bottom:-400px;
  margin-top: 0px;
text-align: center;
  
}
.fvue2 {
margin-top: 300px;
text-align: center;
 animation: fadeIn;
  animation-duration:5s;
  
}
.catch {

  height:300px;
  width:1000px;
text-align: center;
  align-content: center;
  animation: fadeIn;
  animation-duration:3s;
 
}

.text{
 animation: fadeIn;
  animation-duration:3s;
  font-size: 40px;
  text-align: center;
}
</style>