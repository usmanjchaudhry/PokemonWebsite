

<template>
    <div class="login">
      
 <Form msg="Welcome to Your Vue.js App"/>

  </div>
</template>



<script>

import Form from '@/components/Form.vue'

export default {
  name: 'Home',
  components: {
    Form
  }
}
</script>

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

img {
  margin-left: 300px;
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