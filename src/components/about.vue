<template>
  <div class="aboutUs">
    <div class="mainLogo"></div>
    <div class="image1"></div>
    <div class="image2"></div>
    <div class="image3"></div>
    <div class="image4"></div>
  </div>
  
</template>

<script>
export default {
  name: 'about',
  props: {
    msg: String
  }
}
</script>

<style>
  .aboutUs{
    width: 100px;
    height: 100px;
    border : 1px soild red;
  }
  .image1{
    width: 100px;
    height: 100px;
    border : 1px soild red;
  }
  .image2{
    border : 1px soild red;
  }
  .image3{
    border : 1px soild red;
  }
  .image4{
    border : 1px soild red;
  }

</style>
