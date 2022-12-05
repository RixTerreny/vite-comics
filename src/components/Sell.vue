<script>
export default{
    props:['listaProdotti']
}
</script>

<template>
<div class="py-5">
    <div class="container  text-white d-flex flex-column">
        <h4 id="current-series" class="bg-primary"> CURRENT SERIES</h4>
        <div class="row">

            <div v-for="item in listaProdotti" class="col-2 mb-5">
                <div><img :src="item.thumb" alt=""></div>
                <h6 class="mt-3">{{item.series}}</h6>
            </div>

        </div>

        <div class=" text-center">
            <button class="btn btn-primary px-5">LOAD MORE</button>
        </div>
    </div>
        
</div>
</template>

<style scoped lang="scss">
@use '../styles/general.scss' as *;
div{
    background-color: $dark-grey;
}


#current-series{
    margin-top: -70px;
    margin-bottom: 30px;
    padding: 1rem;
    height: 60px;
    width: 245px;
}

button{
    border-radius: 0;
}
</style>