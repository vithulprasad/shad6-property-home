<script setup>

</script>



<template>
  <div class="container-fluid position-relative">
    <div class="position-absolute top-0 start-50 translate-middle position-relative ">
        <div class="position-absolute top-100 start-50 translate-middle pb-4">✨</div>
        <!-- <div class="position-absolute top-100  translate-middle pb-5">D</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">i</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">s</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">c</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">o</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">v</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">e</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">r</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5"> </div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">Y</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">o</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">r</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">D</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">r</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">e</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">a</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">m</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5"> </div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">P</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">r</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">o</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">p</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">e</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">r</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">t</div>
        <div class="position-absolute top-100 start-50 translate-middle pb-5">y</div> -->
     
        <div class="round-Box">
            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 35 34" fill="none">
               <path d="M6.875 27.625L28.125 6.375M28.125 6.375L12.1875 6.375M28.125 6.375V22.3125" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg> 
        </div>
    
    </div>
  <div class="row flex-column flex-xxl-row ">
    <div class="col-xxl-6 order-xxl-2">
    </div>
    <div class="col-xxl-6 order-xxl-1">
      <div class="mx-5 my-3">
        <h2>Discover Your Dream Properties With Estatein</h2>
      </div>
      <div class="mx-5 ">
         <p>Your journey to finding the perfect property begins here. Explore our listings to find the home that matches your dreams.</p>
      </div>
      <div class="mx-5 my-5">
          <div>
            <button type="button" class="btn btn-back text-white border border-dark mx-2 py-2">Learn More</button>
            <button type="button" class="btn btn-info mx-2 py-2">Browse Properties</button>
          </div>
      </div>
      <div class="d-flex w-full ">
        <div class="card  px-3  m-2 one">
          <div class="w-38 text">  <h2 class="text-start ">200+</h2></div>
          <div ><p>Happy Customers</p></div>
        </div>
        <div class="card px-3 m-2 two">
            <div>  <h2>10K+</h2></div>
            <div ><p>Properties For Clients</p></div>
        </div>
        <div class="card  px-3 m-2 three">
            <div >  <h2>16K+</h2></div>
            <div ><p>Years of Experience</p></div>
        </div>
      </div>

    </div>
  </div>
</div>

   
   
   </template>
<style>
.btn.btn-info.mx-2.py-2{
   background: var(--Purple-60, #703BF7);
;
}
  .col-xxl-6.order-xxl-2{
    flex: 1 0 0;
    align-self: stretch;
    background: linear-gradient(238deg, #2A213F 8.76%, rgba(25, 25, 25, 0.00) 50.09%), url("assets/Image.png"), rgb(27, 26, 26) 50% / cover no-repeat;
    background-repeat: no-repeat;
    background-size: cover;
    background-position:center;
  }
  .position-absolute.top-0.start-50.translate-middle{
    display: flex;
    width: 100px;
    height: 100px;
    padding: 23.727px;
    align-items: flex-start;
    margin-top: 200px;
    border-radius: 159.091px;
   border: 1.591px solid var(--Grey-15, #262626);
   background: var(--Grey-08, #141414);

  }
  .round-Box{
     width: 50.545px;
     height: 50.545px;
     flex-shrink: 0;
     padding:10px;
     border-radius: 89.091px;
     border: 1.591px solid var(--Grey-15, #262626);
     background: var(--Grey-10, #1A1A1A);
  }
  .letter1{
    transform: rotate(172.024deg);
    color: #FFF;

    font-family: Urbanist;
    font-size: 15.008px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
  }
  .card.px-3.m-2.one{
    background:rgb(27, 26, 26);
    width:200px;
    justify-content: start;
}
.card.px-3.m-2.two{
  background:rgb(27, 26, 26);
  width:200px;
}

.card.px-3.m-2.three{
  background:rgb(27, 26, 26);
  width:200px;
}
  @media (max-width: 1200px) {
    .position-absolute.top-50.start-50.translate-middle.position-relative {
       
        margin-left: -300px;
      
    }
    .card.px-3.m-2.one{
     width:45%;
 
}
.card.px-3.m-2.two{
     width:45%;
  
}

.card.px-3.m-2.three{
    width:100%;
    display:flex;
    align-items:center;
    justify-content:center;
    background:gray;
}
.d-flex.w-full {
  display: flex;
  flex-wrap: wrap;
}
}

  .col-xxl-6.order-xxl-1{
    padding:100px 50px 100px 50px;
    gap:10px
  }
 
  p{
    color:gray;
  }
  @media (max-width: 980px) {
    .col-xxl-6.order-xxl-1{
    padding: 0;
  }
  

}
</style>

