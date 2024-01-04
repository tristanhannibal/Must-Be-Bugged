<script setup>
</script>


<template>
    <div class="apply">
        <div class="wrap-iframe"><iframe  src="https://docs.google.com/forms/d/e/1FAIpQLScgVcO3D-I2YCQzvm7mJEAlAkUlO5ip7Kcu1rFb_-msNQmOdQ/viewform" width="700px" height="600" frameborder="0" marginheight="0" marginwidth="0">Loading</iframe></div>
    </div> 
  </template>
  
  <style>
  .wrap-iframe{
    background:url(/src/assets/loading.gif) center center no-repeat;
    background-size: 25%;
  }

.apply{
    display: flex;
    align-items: center;
    flex-direction: column;
  }
 @media (min-width: 1024px) {
    .apply {
      min-height: 60vh;
      max-height: 60vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      max-width: 700px;
      width: 100%;
    }
  }
  </style>
  