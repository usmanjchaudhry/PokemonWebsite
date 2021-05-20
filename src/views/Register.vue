<template>
  <div class="register">
    
    <b-container>
  <!-- Content here -->

<img class = "regPic" 
      src="https://th.bing.com/th/id/OIP.SO2ToQqfLHc8jy16ub1yaQHaGm?pid=ImgDet&rs=1"
>

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

    
    <b-button class="btn btn-primary" href="about"  type="reset" variant="danger">Submit</b-button>
  
  
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

<style scope>
.form-group {
  text-align: left;
  font-size: 30px;
  font-weight: bold;
  
}

.regPic {
  margin-left: 300px;
  padding: 100px 0px;
}


.btn-primary {
  display: block;
  width: 15%;
  float: left;
  font-weight: bold;
  margin: 20px 12px;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
  font-size: 70px;
  padding: 50px 0px;
}


</style>