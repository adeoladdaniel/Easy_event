<template>
<div>
 <SideBar/>


<div class="header">
        <h1>find event  <br/>near you</h1>
        <p>The best way to host an events, <br/> sell event tickets.</p>

        <img class="landing_img" src="img/assets/_52CD8CF3-B2FD-48AD-9C97-F578A403D841_preview.svg"/>
            <img class="landing_mobile" src="img/assets/Bitmap.svg"/>


<div class="search-box">
<form>
    <img src="img/icons/Shape.svg"/>
    <input  class=" event_input" placeholder="Find event near you"/>

    <img  class="path" src="img/icons/Path_6243.svg"/>


    <img  class="loc_icon" src="img/icons/surface1-2.svg"/>

    <input  class=" location_input" placeholder="Location"/>

    <img   class="loc_icon_i" src="img/icons/Path_5275.svg"/>

    <button class="search_but"> Search</button>




</form>
</div>

</div>

<Cards/>
</div>
</template>

<script>
// @ is an alias to /src
import SideBar from '@/components/SideBar.vue';
import Cards from '@/components/Cards.vue'

import users from './user.json'




export default {
  name: 'Home',
  components: {
    SideBar,
    Cards
    
  },

  data(){
     return{
        users
     }
  },
  mounted(){
     console.log(typeof(users));
  }
}
</script>

<style lang="scss">
.landing_img{
        position: absolute;
    right: 0;
    top: 10rem;
    width: 64%;
        z-index: -2;
}

.header{
    h1{
        padding: 10rem 1rem 1rem 6rem;
    font-weight: bold;
        font-size: 4rem;
    }
    p{
        padding: 2rem 1rem 1rem 6rem;

    }
}
.search-box{
     box-shadow: 0px 17px 43px #7373733d;
    padding: 2rem;
    background: white;
    margin: 2rem 13rem 2rem 5rem;
       padding: 1.5rem 2rem 1.5rem 5rem;
   
}
.event_input{
        border: none;
    padding: 0rem 0rem 0rem 3rem;
    outline: none;
}
.event_input:active{
    outline: none;
}
.search_but{
    padding: 1rem 3rem;
    border: none;
    margin: 0rem 1rem;
    position: absolute;
    right: 13rem;
    background: red;
    color: white;
    border-radius: 5px;
    
}
.path{
    padding:0rem 6rem;
}

.loc_icon{
    padding: 0rem 2rem;
}
.loc_icon_i{
 padding: 1rem 0rem;
}


.location_input{
    border: none;
    outline: none;
}
.landing_mobile{
    display: none;
}

</style>