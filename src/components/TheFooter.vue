<script>
export default{
    data(){
        return{
            titleList:[
                "DC COMICS",
                "SHOP",
                "DC",
                "SITES"
            ],
            dcComics:[
                "Character",
                "Comics",
                "Movie",
                "TV",
                "Games",
                "Videos",
                "News"
            ],
            
            img:[
                "footer-facebook.png",
                "footer-twitter.png",
                "footer-youtube.png",
                "footer-pinterest.png",
                "footer-periscope.png"
            ]
        }
    }
}
</script>

<template>
    <div class="bg-img ">
        <div class="container  d-flex justify-content-between">
            <div class="mt-5">
                <div v-for="element in titleList">
                    <h5 class="text-white">{{element}}</h5>
                    <a v-for="element in dcComics" class="">{{element}}</a>
                </div>
            </div>
            <div class="dc-bg">
            </div>
        </div>
    </div>

    <div class="bg-grey">
        <div class="container d-flex justify-content-between align-item-center py-4">
            <button>SIGN-UP NOW!</button>

            <div class="d-flex  align-item-center">
                <div class="follow fw-semibold me-4">FOLLOW US</div>
                <div v-for="element in img" class="resize ms-3"><img :src="element" alt=""></div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../styles/general.scss' as *;
.bg-img{
    background-image: url(../assets/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

.dc-bg{
    background-image: url(../assets/dc-logo-bg.png);
    height: 350px;
    width: 600px;
    background-repeat: no-repeat;
    background-position: 0 50% ;
}

a{
    font-size: 0.9rem;
    color: rgb(126, 126, 126);
}

.bg-grey{
    background-color: $grey;
}

.resize{
    width: 2.3rem;
}

.follow{
    font-size: 1.7rem;
    color: $dc;
}

button{
    background-color: $grey;
    color: white;
    border-color: $dc;
}

</style>