<script>
export default{}
</script>

<template>
    <div class="d-flex container pt-3 pb-4 justify-content-between">
        <div class="resize">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div class="d-flex align-items-center mt-3">
            <ul class="d-flex">
                <li class="mx-2 fw-semibold"><a href="">characters</a></li>
                <li class="mx-2 fw-semibold"><a href="">comics</a></li>
                <li class="mx-2 fw-semibold"><a href="">movies</a></li>
                <li class="mx-2 fw-semibold"><a href="">tv</a></li>
                <li class="mx-2 fw-semibold"><a href="">games</a></li>
                <li class="mx-2 fw-semibold"><a href="">collectibles</a></li>
                <li class="mx-2 fw-semibold"><a href="">videos</a></li>
                <li class="mx-2 fw-semibold"><a href="">fans</a></li>
                <li class="mx-2 fw-semibold"><a href="">news</a></li>
                <li class="mx-2 fw-semibold"><a href="">shop</a></li>
            </ul>
        </div>
    </div>
</template>


<style scoped lang="scss">
@use '../styles/general.scss' as *;

li{
    text-transform: uppercase;
    font-size: 0.92rem;
}

a{
    color: $dark-grey;
} 

img{
    width: 100%;
}

.resize{
    width: 80px;
}
</style>