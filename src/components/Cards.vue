<template>
    <div>
        <div class="card_section">
                <div class="card">

                    <img src="img/assets/Bitmap.svg"/> 
                          <span>Easy Event Opening <br/>Lunch Party</span>

                          <p>The basic of the legendary language</p>
                          <p class="date"> Fri, Apr 3, 8:30 AM</p>

                          <div class="tag">
                              Free
                          </div>
                          <img src="img/assets/icons/love.svg"/>
                </div>

                  <div class="card">

                    
                    <img src="img/assets/Bitmap.svg"/>
                          <span>Easy Event Opening <br/>Lunch Party</span>

                          <p>The basic of the legendary language</p>
                          <p class="date"> Fri, Apr 3, 8:30 AM</p>

                          <div class="tag">
                              Free
                          </div>
                </div>


                     <div class="card">

                    
                    <img src="img/assets/Bitmap.svg"/>
                          <span>Easy Event Opening <br/>Lunch Party</span>

                          <p>The basic of the legendary language</p>
                          <p class="date"> Fri, Apr 3, 8:30 AM</p>

                          <div class="tag">
                              Free
                          </div>
                </div>


                     <div class="card">

                    
                    <img src="img/assets/Bitmap.svg"/>
                          <span>Easy Event Opening <br/>Lunch Party</span>

                          <p>The basic of the legendary language</p>
                          <p class="date"> Fri, Apr 3, 8:30 AM</p>

                          <div class="tag">
                              Free
                          </div>
                </div>


        </div>

    

    </div>
</template>



<style lang="scss" >
.card_section{

        display: flex;
    justify-content: space-evenly;
    padding-top: 7rem;
}
.card{
        padding: 1rem;
    border: none !important;
    box-shadow: #949494 0px 0px 13px -5px;
        height: 310px !important;

    p{
        font-size: 12px;
    }
}

.date{
    color:red;
    font-size: 10px;
}
.tag{
        position: relative;
    bottom: 16.3rem;
    background: red;
    width: 3rem;
    color: white;
    left: 1rem;
    text-align: center;
    padding: 3rem 0rem 0rem 0rem;
}

@media screen and (max-width: 600px) {
.card_section{

    display: grid;
    justify-content: stretch;
    padding-top: 7rem;
    grid-gap:30px;
}

.logo {
    width: 86%;
    padding: 0rem;
}

.card{
height: 100% !important;

.tag{
    bottom: 26.3rem;
}

   img{
       width: 100%;
   }

p{
    padding: 1rem;

}
span{
    padding: 1rem;
}

padding: 0rem;
}



.landing_img {
display: none;
}

.loc_icon{
    display: none;
}
.loc_icon_i{
    display: none;
}
.search_but{
    display: none;
}

.location_input{
    display: none;
}
.path{
    display: none;
}
.search-box{
    margin: 4rem 0rem 2rem 3rem !important;
    padding: 2rem 0rem 2rem 5rem !important;
}

.header{
     h1 {
    padding: 19rem 1rem 1rem 3rem !important;
    font-weight: bold;
    font-size: 3rem; 
}
p {
    padding: 1rem 1rem 1rem 3rem !important;
}


}
}
</style>