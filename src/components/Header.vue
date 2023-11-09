<template>
    <div>
     <div class="container d-flex justify-content-between pt-4 mb-4 " >
        <img src="../assets/images/dc-logo.png" alt="">
        <div>
            <ul class="d-flex list-unstyled mt-4">
                <li v-for="menuitems in arraymenu">{{menuitems}}</li>
                
            </ul>
        </div>
     </div>
    </div>
</template>

<script>
export default {
    name:'Header',
    data() {
        return {
            arraymenu:[
                'CHARACTERS',
                'COMICS',
                'MOVIE',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP',
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.container{
    height: 100px;
    font-family: 'Open Sans Condensed'
}
img{
    width: 80px;
    height: 80px;
}
li{
    margin-left: 25px;
    font-size: 0.9em;
}


</style>