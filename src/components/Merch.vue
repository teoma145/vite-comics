<template>
    <div class="merch">
      <div class="container d-flex  h-100 flex-wrap pe-5">
        <div class="d-flex align-items-center pt-2 pb-2 ms-4  col-12 col-md-2">
            <img src="../assets/images/buy-comics-digital-comics.png" alt="">
             <div class="text-white ms-1  ">DIGITAL COMIC</div>
        </div>
        <div class="d-flex align-items-center pt-2 pb-2 ms-4 col-12 col-md-2 ">
            <img src="../assets/images/buy-comics-merchandise.png" alt="">
             <div class="text-white ms-1 ">DC MERCHANDISE</div>
        </div>
        <div class="d-flex align-items-center pt-2 pb-2  ms-4 col-12 col-md-2">
            <img src="../assets/images/buy-comics-subscriptions.png" alt="">
             <div class="text-white ms-1  ">SUBSCRIPTION</div>
        </div>
        <div class="d-flex align-items-center pt-2 pb-2  ms-4 col-12 col-md-2">
            <img src="../assets/images/buy-comics-shop-locator.png" alt="">
             <div class="text-white ms-1 ">COMIC SHOP LOCATOR</div>
        </div>
        <div class="d-flex align-items-center pt-2 pb-2  ms-4 col-12 col-md-2">
            <img src="../assets/images/buy-dc-power-visa.svg" alt="">
             <div class="text-white ms-1 ">DC POWE VISA</div>
        </div>
        
    
      </div>
    </div>
</template>

<script>
export default {
    name:'Merch',
    data() {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.merch{
    
    background-color:rgb(57, 123, 221);
    overflow-x: hidden;
    padding: 20px 0 20px 0;
}
img{
    width: 50px;
    height: 60px;
}
</style>