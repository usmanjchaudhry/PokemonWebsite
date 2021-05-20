

<template>
    <div class="login">
        <b-container>
  <!-- Content here -->

<div>
  <img class = "loginpic" src="https://th.bing.com/th/id/R92376cd31daa2b778d0c8c972f4ff15e?rik=tlNWq4EqkBli3g&pid=ImgRaw"
  height = 50%;
  width = 50%;
  >
</div>

<div class="container">
<h2>Sign in</h2>
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
</div>

</b-container>
    
  </div>
</template>

<style scoped>
.form-group {
  text-align: left;
  font-weight: bold;
  font-size: 25px;
}

h2 {
  text-align: left;
  font-weight: bold;
  font-size: 50px;
  margin: 30px 0px;
}

.btn-primary {
  display: block;
  width: 15%;
  height: 80%;
  float: left;
  margin: 20px 12px;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
  text-align: center;
  font-weight: bold;
  font-size: 20px;
  padding: 20px 20px;
}



</style>