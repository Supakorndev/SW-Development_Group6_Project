<template>
<div>
  <nav class="navbar navbar-expand-lg navbar-light" style="background-color:#e3cb12">
    <div class="container-fluid">
        <ul class="navbar-nav">
           
          <li class="nav-item">
           
            <router-link class="navbar-brand on-active" aria-current="page" to="/">
            <img src="./assets/compass.svg" alt="" width="30" height="24" class="d-inline-block align-text-top"> 
            Home
            </router-link>
          </li>
        </ul>
    </div>
  </nav>
   <router-view/>
</div>

</template>

<script>
import * as name from 'bootstrap/dist/js/bootstrap.esm'
export default {
  name:'App',
  data() {
    return {
      
    }
  },
  mounted(){
    // console.log(Alert);
    console.log(name.Alert)
  }
}
</script>