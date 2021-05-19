<template>
  <div class="home">

<b-container>
    <h1>This is a Home page</h1>
  <p> We will put an Intro here to the website </p>
  

  <img class="catch" src="../assets/PokemonCatchEmAll.jpg">
  
</b-container>


  </div>

  </template>




        <!-- <b-container>
 

<form method="post">
	<div class="form-group">
    	<label for="Username">Username</label>
		<input type="text" class="form-control" name="username" placeholder="Username" required="true">  
	</div>
    <div class="form-group">
    	<label for="Password">Password</label>
		<input type="password" class="form-control" name="password" placeholder="Password" required="true"> 
	</div>
  
  
    <button type="submit" class="btn btn-primary">Login</button>
    <b-button class="btn btn-primary" href="register"  type="reset" variant="danger">Register</b-button>
  
  
</form>

</b-container> -->
    
  


<script>


export default {
  name: "Home",
  components: {
    
  },
};
</script>

<style scoped>
.catch {
  text-align: center;
  height:800px;
  width:1200px;
}

body{
  background-color:black;
}
</style>