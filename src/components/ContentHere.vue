<template>
    <div class="contenthere  d-flex align-items-center ">
        <div class="container">
            <div class="row gy-2">
                <div class="col-12 col-md-2 col-lg-2" v-for="(comic, index) in comicsData" :key="index">
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

</style>