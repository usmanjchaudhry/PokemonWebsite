<template>
    <div>
        <h3> My Profile </h3>
       <app-status />  

<img class="profileImg" 
     src="https://media1.tenor.com/images/83592060cb2d2cf51e98a5809aeb60d3/tenor.gif?itemid=16734116"
     >

<!--
<router-link to="/login">Go to Login Page</router-link> -->
    </div>
</template>
<!--
<script>
import Status from '../components/Status.vue'

    export default {
        components: {
           'app-status': Status
        }
    }
    </script>
-->
    <style scoped>

    h3 {
        font-size: 50px;
        font-weight: bold;
        padding: 50px 50px;
    }

    .profileImg {
        margin-left: 600px;
        height: 500px;
        margin-top: 200px;
        
    }
    </style>