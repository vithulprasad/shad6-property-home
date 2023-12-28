<script setup>

</script>



<template>
  <div class="container-fluid position-relative">
    <div class="position-absolute top-50 start-50 translate-middle position-relative ">
        <div class="position-absolute top-100 start-50 translate-middle pb-5">✨</div>
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
            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="34" viewBox="0 0 35 34" fill="none">
               <path d="M6.875 27.625L28.125 6.375M28.125 6.375L12.1875 6.375M28.125 6.375V22.3125" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg> 
        </div>
    
    </div>
  <div class="row flex-column flex-xxl-row p-2">
    <div class="col-xxl-6 order-xxl-2">
    </div>
    <div class="col-xxl-6 order-xxl-1">
      <div class="mx-5 my-5">
        <h1>Discover Your Dream Properties With Estatein</h1>
      </div>
      <div class="mx-5 my-5">
         <p>Your journey to finding the perfect property begins here. Explore our listings to find the home that matches your dreams.</p>
      </div>
      <div class="mx-5 my-5">
          <div>
            <button type="button" class="btn btn-back text-white border border-dark mx-2 py-3">Learn More</button>
            <button type="button" class="btn btn-info mx-2 py-3">Browse Properties</button>
          </div>
      </div>
      <div class="d-flex w-full">
        <div class="card bg-dark px-2 d-flex justify-center align-items-center  m-2 one">
          <div>  <h1>200+</h1></div>
          <div ><p>Happy Customers</p></div>
        </div>
        <div class="card bg-dark px-2 d-flex justify-center align-items-center m-2 two">
            <div>  <h1>10K+</h1></div>
            <div ><p>Properties For Clients</p></div>
        </div>
        <div class="card bg-dark d-flex justify-center align-items-center px-1 m-2 three">
            <div >  <h1>16K+</h1></div>
            <div ><p>Years of Experience</p></div>
        </div>
      </div>

    </div>
  </div>
</div>

   
   
   </template>
<style>
  .col-xxl-6.order-xxl-2{
    background-image: url("https://i.pinimg.com/564x/04/e0/21/04e021b99753e2e0c42aa49ab48ac655.jpg");
 
    height: 700px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position:center;
  }
  .position-absolute.top-50.start-50.translate-middle{
    display: flex;
    width: 175px;
    height: 175px;
    padding: 47.727px;
    align-items: flex-start;
    gap: 15.909px;
    border-radius: 159.091px;
   border: 1.591px solid var(--Grey-15, #262626);
   background: var(--Grey-08, #141414);

  }
  .round-Box{
     width: 79.545px;
     height: 79.545px;
     flex-shrink: 0;
     padding:20px;
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
  @media (max-width: 1200px) {
    .position-absolute.top-50.start-50.translate-middle.position-relative {
       
        margin-left: -300px;
        background: red;
    }
    .card.bg-dark.px-2.d-flex.justify-center.align-items-center.m-2.one{
     width:45%;
     background:blue;
}
.card.bg-dark.px-2.d-flex.justify-center.align-items-center.m-2.two{
     width:45%;
     background:orange;
}
.card.bg-dark.d-flex.justify-center.align-items-center.px-1.m-2.three{
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
    padding:100px 100px 100px 100px;
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

