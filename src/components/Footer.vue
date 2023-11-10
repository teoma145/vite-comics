<template>
    <div class="footer pb-4">
       <div class="container d-flex justify-content-between flex-wrap">
          <div class="mt-5 ">
            <a href="" class="buttonfoot text-decoration-none ">SIGN UP NOW</a>
          </div>
          <div class="d-flex flex-wrap">
            <h2 class="mt-5">FOLLOW US</h2>
            <div>
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-facebook.png" alt="">
            </div>
            
          </div>
          
        </div>
    </div>
</template>

<script>
export default {
    name:'Footer',
    data() {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.footer{
    background-color: rgb(48, 48, 48);
    
}
.buttonfoot{
    border: 1px solid rgb(57, 123, 221);
    color: white;
    padding: 10px;
    
}
h2{
    font-size: 1.3em;
    color: rgb(57, 123, 221);
}
img{
    margin-left: 10px;
    margin-top: 45px;
    height: 25px;
}
</style>