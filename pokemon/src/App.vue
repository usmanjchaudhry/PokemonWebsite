<template>
  <div id="app">
    <!-- for animations if this doesnt work just do command npm install animate.css --save -->
  <link href="https://cdn.jsdelivr.net/npm/animate.css@3.7.2" rel="stylesheet" type="text/css">

  
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>|
      <router-link to="/profile">Profile</router-link>
    </div> -->
   <div>
 
  <b-navbar  toggleable="lg" type="dark" variant="info">
    
    <b-navbar-brand  href="#">
    <img src="./assets/PokemonLogo.png" width="auto" height="40 px" /> </b-navbar-brand>


    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
         <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item href="about">Pokemon</b-nav-item>
        <b-nav-item href="Profile">Profile</b-nav-item>
     
        
       
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
       

      <!--New Comment -->
      <!--Another New Comment -->

        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <em>Account</em>
          </template>
          <b-dropdown-item href="login">Login</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: url("./assets/pokemon-ball.png");
  
  
   
}



.navbar-dark .navbar-nav .nav-link{
      color:white!important
    }


#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}


#nav a.router-link-exact-active {
  color: #42b983;
}

img:hover {
  animation:heartBeat;
  animation-duration: 2s;
}


</style>
