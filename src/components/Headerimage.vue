<template>
    <div class="imgcont">
       <img src="../assets/images/jumbotron.jpg" alt="">
    </div>
</template>

<script>
  name:'Headerimage';
    export default {
        
    }
</script>

<style lang="scss" scoped>
.imgcont{width: 100%;
    height: 500px;
    overflow: hidden;
    }
    @media (max-width: 768px) {
  .imgcont img {
    width: 100%; 
     
  }
  .imgcont{
    height: 200px;
  }
}
</style>