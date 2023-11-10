<template>
    <div class="maindc">
      <div class="container d-flex pb-5">
         <div class="col-3 col-md-1">
            <h2 class="fs-6 text-white mt-5 ">DC COMICS</h2>
            <ul class="list-unstyled">
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Video</li>
                <li>News</li>
            </ul>
            <div class="col-3 col-md-1">
                <h2 class="fs-6 text-white mt-3">DC COMICS</h2>
                <ul class="list-unstyled">
                <li>Shop Dc</li>
                <li>Shop Dc collectibles</li>
            </ul>
            </div>
         </div>
         <div class="col-3 col-md-1">
            <h2 class="fs-6 text-white mt-5 ms-5">DC</h2>
            <ul class="list-unstyled ms-5 ">
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Video</li>
                <li>News</li>
                <li>Games</li>
                <li>Video</li>
                <li>News</li>
            </ul>
         </div>
         <div class="col-3 col-md-1">
            <h2 class="fs-6 text-white mt-5 ms-5 ps-3">SITES</h2>
            <ul class="list-unstyled ms-5 ps-3">
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
               
            </ul>
         </div>
         <div class="imglog">
            <img src="../assets/images/dc-logo-bg.png" alt="">
         </div>
      </div>
     
    </div>
</template>

<script>
export default {
    name:'MainDc',
    data() {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.maindc{
    
    background-image: url(../assets/images/footer-bg.jpg);
    background-size: cover;
    height: 400px;
    overflow: hidden;
    position: relative;
}
ul{
    color: grey;
    
}
.imglog{
    position: absolute;
    top: -70px;
    right: 70px;
}
</style>