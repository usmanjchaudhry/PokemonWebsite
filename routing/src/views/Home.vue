<template>
  <div class="home">
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
</form>
    
  </div>
</template>

<script>


export default {
  name: "Home",
  components: {
    
  },
};
</script>
