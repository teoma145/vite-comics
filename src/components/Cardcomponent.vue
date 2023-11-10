<template>
    <div class="card mt-5 cardheight ">
        <img :src='thumb' class="card-img-top" :alt="series">
    </div>
    <h5 class="card-title text-white  pb-2 ">{{series}}</h5>
</template>

<script>
export default {
    name: 'Cardcomponent',
    props: [
        'thumb',
        'series'
    ]

}
</script>

<style lang="scss" scoped>
img{
    height: 230px;
}
</style>