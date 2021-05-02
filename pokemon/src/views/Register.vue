<template>
  <div class="register">
    <h1>This is a Register page</h1>
    <b-container>
  <!-- Content here -->


<form method="post">
	<div class="form-group">
    	<label for="FirstName">First Name</label>
		<input type="text" class="form-control" name="FirstName" placeholder="Enter your first name" required="true">  
        	</div>
    <div class="form-group">
    	<label for="LastName">Last Name</label>
		<input type="text" class="form-control" name="LastName" placeholder="Enter your last name" required="true"> 
	</div>
    <div class="form-group">
    	<label for="Username">Username</label>
		<input type="text" class="form-control" name="username" placeholder="Username" required="true">  
	</div>
    <div class="form-group">
    	<label for="Password">Password</label>
		<input type="password" class="form-control" name="password" placeholder="Password" required="true"> 
	</div>
  
  
 <!-- Button links to about page for now -->

    
    <b-button class="btn btn-primary" href="about"  type="reset" variant="danger">Register</b-button>
  
  
</form>

</b-container>


  </div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>