<template>
  <div class="hello">
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
     <b-form  @submit="onSubmit"  v-if="show">
      <b-form-group
        id="input-group-1"
        label="User:"
        label-for="input-1"
      >
        <b-form-input
          id="input-1"
          v-model="form.user"
          type="text"
          required
          placeholder="Enter User"
        ></b-form-input>
      </b-form-group>

      <b-form-group id="input-group-2" label="Password:" label-for="input-2">
        <b-form-input
          id="input-2"
          v-model="form.password"
            type="password"
          required
          placeholder="Enter Password"
        ></b-form-input>
      </b-form-group>


    

      <b-button type="submit" class="mr-4" variant="primary">Submit</b-button>
     <b-button class="btn btn-primary" href="register"  type="reset" variant="danger">Register</b-button>
       <h6 class="text-danger mt-4" v-if="con">INCORRECT LOGIN</h6>
      
      
    </b-form>

 </div>
  
       

</b-container>
    

    
  </div>
</template>

<script>

export default {
  name: 'Form',
  data() {
      return {
        form: {
          user: '',
          password: '',
         
        },
        show: true,
        con:false
      }
    },
    methods: {
      onSubmit(evt) {
        evt.preventDefault()
        if (this.form.user=='admin' && this.form.password=='123456') {
          this.$router.push('about')
        } else{
          this.con=true
        }
      },
     
      
    
    }
 
}
</script>