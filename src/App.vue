<script setup>

const image = {
  logoimage:'https://i.ibb.co/yfzCK0y/6111095.jpg',
  alt:'Logoimage',
  title:'Login Forum Image'
}

const label = {
  labelfirst:'First Name',
  labellast:'Last Name',
  labeluser:'User Name',
  labelemail:'Email address',
  labelhide:'We ll never share your email with anyone else.',
  labelpassword:'Password',
  labelsign:'Sign In',
}


</script>



<template>

<div class="main">
        <div class="row gx-0">
          <div class="col-xl-6 logo_section">
            <img class="img-fluid" :src="image.logoimage" :alt="image.alt" :title="image.title">
          </div>
          <div class="col-xl-6 input_section">
            <form>
              <div class="row mb-3">
                <div class="col-xl-6 borderl">
                  <label for="exampleInputName" class="form-label">{{ label.labelfirst }}</label>
                  <input type="text" class="form-control" id="exampleInputName">
                </div>
                <div class="col-xl-6">
                  <label for="exampleInputName" class="form-label">{{ label.labellast }}</label>
                  <input type="text" class="form-control" id="exampleInputName">
                </div>
              </div>
              <div class="mb-4">
                <label for="exampleInputName" class="form-label">{{ label.labeluser }}</label>
                <input type="text" class="form-control" id="exampleInputName">
              </div>
              <div class="mb-2">
                <label for="exampleInputEmail1" class="form-label">{{ label.labelemail }}</label>
                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                <div id="emailHelp" class="form-text">{{ label.labelhide }}</div>
              </div>
              <div class="mb-4">
                <label for="exampleInputPassword1" class="form-label">{{ label.labelpassword }}</label>
                <input type="password" class="form-control" id="exampleInputPassword1">
              </div>
              <button type="submit" class="btn btn-primary">{{ label.labelsign }}</button>
            </form>
          </div>
  
        </div>
    </div>






  
</template>

<style scoped>








</style>
