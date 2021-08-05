<template>



  <div>
<div class="nav_mobile">
<img class="logo"  src="img/assets/Group_2823.svg"/>

    <div id="app">
    <img @click='toggle = !toggle' src="img/icons/CombinedShape.svg"/>


</div>
    <img src="img/icons/Shape.svg"/>

        <button  class="easy_but">Join</button>



</div> 
 <div class="dropdown-mobile" v-show='toggle'>Sign in</div>
 <div class="dropdown-mobile" v-show='toggle'>How it works</div>

<div class="navm">

  <b-navbar toggleable="lg" >
    <b-navbar-brand href="#" ><img class="logo"  src="img/assets/Group_2823.svg"/></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
     

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto nav links">
        <b-nav-item href="#"  class="space">create event</b-nav-item>
        <b-nav-item href="#" class="space" >how it works</b-nav-item>
        <b-nav-item href="#" class="space">help</b-nav-item>
        <button  class="easy_but">Join</button>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</div>


</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<script>
export default {

 el: '#app',
 data () {
   return {
     toggle: true
   }
 },
}
</script>
<style lang="scss">

.navbar-dark .navbar-nav .nav-link {
    color: black !important;
}

.logo{

width: 86%;
    padding: 2rem 2rem 2rem 6rem;
}

.dropdown-mobile{
  display: none;
}
.links{
      padding-right: 3rem;
}
.space{
  padding-right: 2rem;
}
.easy_but{
      width: 88px;
    height: 39px;
    border: none;
    border-radius: 5px;
    background: black;
    color: white;
    box-shadow: #ff000038 10px 0rem 1rem 0rem;
}

.nav_mobile{
  display: none;
}
@media screen and (max-width: 600px) {


  .landing_mobile{
    display: block !important;
    width: 100%;
           position: absolute;
    right: 0;
    top: 10rem;
        z-index: -2;
}
.navm{
  display:none;
}
.nav_mobile{
      display: flex;
    justify-content: space-around;
    padding: 10px 2px;
}
.logo{
  width: 30% !important;
}

.dropdown-mobile{
      background: #DEE2E8;
    padding: 1rem;
    display: block;
}

}

</style>
