<template>
  <div class="home">

<div class="dude">
  <img class="catch" src="https://techcrunch.com/wp-content/uploads/2016/07/gettyimages-482740284.jpg">
  
</div>


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

.dude{
  display: flexbox;
  margin-left: unset;
  margin-right: unset;
  margin-top: 100px;
  margin: 0 !important;
  
}
.catch {
  text-align: center;
  height:800px;
  width:1200px;
  animation: fadeIn;
  animation-duration:5s;
  margin-left: 0px;
}

body{
  background-color:black;
}
</style>