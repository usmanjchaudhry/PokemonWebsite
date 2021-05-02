<template>
  <div class="home">
        <b-container>
  <!-- Content here -->


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
    <b-button class="btn btn-primary"  type="reset" variant="danger">Register</b-button>
  
  
</form>

</b-container>
    
  </div>
</template>

<script>


export default {
  name: "Home",
  components: {
    
  },
};
</script>

