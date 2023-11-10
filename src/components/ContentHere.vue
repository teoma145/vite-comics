<template>
    <div class="contenthere  d-flex align-items-center pb-5 pt-3 ">
        <div class="container">
            <div class="bg-info currentser">
                <h3 class="text-white fs-4">CURRENT SERIES</h3>
            </div>
            <div class="row gy-2">
                <div class="col-12 col-md-4 col-lg-2 " v-for="(comic, index) in comicsData" :key="index">
                    <Cardcomponent :thumb="comic.thumb" :series="comic.series" />
                </div>

            </div>
        </div>
     
    </div>
</template>

<script>
import jsonData from '../data/dc-comics.json';
import Cardcomponent from './Cardcomponent.vue';
export default {
    name:'ContentHere',
    components: {
        Cardcomponent
    },
    data() {
        

        return {

            comicsData: jsonData
        }
    },
    
}
</script>

<style lang="scss" scoped>

.contenthere{
    
    background-color: rgb(36, 33, 33);
}
.currentser{
    width: 200px;
    padding: 5px;
    position: absolute;
    top: -40px;
    left: 0;
    
}
.container{
    position: relative;
}

</style>