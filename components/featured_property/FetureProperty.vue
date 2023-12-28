<script setup lang="ts">

</script>

<template>
    <div class="p-5">
        <div><h1>Featured Properties</h1></div>
        <div class="d-flex">
            <p>Explore our handpicked selection of featured properties. Each listing offers a glimpse into exceptional homes and investments available through Estatein. Click "View Details" for more information.</p>
            <button type="button" class="btn btn-dark  font-weight-light "><p class="m-0">view all properties</p></button>
        </div>
        <div>
            <CardSingle/>
        </div>
        <div class="d-flex justify-content-between my-3 border-top-dark">
            <div>
                <p>01 of 10</p>
            </div>
          <div class="d-flex ">
            <div><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M20.4004 12.0001C20.4004 12.4971 19.9974 12.9001 19.5004 12.9001L6.73489 12.9L11.7242 17.6513C12.0825 17.9958 12.0937 18.5656 11.7491 18.9238C11.4046 19.2821 10.8349 19.2933 10.4766 18.9488L3.87659 12.6488C3.70012 12.4791 3.60039 12.2449 3.60039 12C3.60039 11.7552 3.70012 11.521 3.87659 11.3513L10.4766 5.0513C10.8349 4.70679 11.4046 4.71796 11.7491 5.07625C12.0937 5.43455 12.0825 6.00429 11.7242 6.3488L6.73489 11.1L19.5004 11.1001C19.9974 11.1001 20.4004 11.503 20.4004 12.0001Z" fill="#808080"/>
            </svg></div>
            <div>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M3.59961 11.9999C3.59961 11.5029 4.00255 11.0999 4.49961 11.0999L17.2651 11.0999L12.2758 6.3487C11.9175 6.00418 11.9063 5.43445 12.2509 5.07615C12.5954 4.71786 13.1651 4.70669 13.5234 5.0512L20.1234 11.3512C20.2999 11.5209 20.3996 11.7551 20.3996 11.9999C20.3996 12.2448 20.2999 12.479 20.1234 12.6487L13.5234 18.9487C13.1651 19.2932 12.5954 19.282 12.2509 18.9237C11.9063 18.5655 11.9175 17.9957 12.2758 17.6512L17.2651 12.8999L4.49961 12.8999C4.00255 12.8999 3.59961 12.497 3.59961 11.9999Z" fill="white"/>
            </svg>
            </div>
          </div>   
        </div>
    </div>
</template>

<style  scoped>
@media (max-width: 980px) {
    button{
    display:none;
  }
}
</style>