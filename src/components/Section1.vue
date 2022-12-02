<script>
export default{
    data(){
        return{
            listaProdotti:[
                {
                    prodotto: 'DIGITAL COMICS',
                    percorso: 'buy-comics-digital-comics.png'
                },
                {
                    prodotto: 'DC MERCHANDISE',
                    percorso: 'buy-comics-merchandise.png'
                },
                {
                    prodotto: 'SUBSCRIPTION',
                    percorso: 'buy-comics-subscriptions.png'
                },
                {
                    prodotto: 'COMIC SHOP LOCATOR',
                    percorso: 'buy-comics-shop-locator.png'
                },
                {
                    prodotto: 'DC POWER VISA',
                    percorso: 'buy-dc-power-visa.svg'
                },
            ]
        }
    },
}

</script>

<template>
    <div class="bg-recolor">
        <div class="container p-5 d-flex justify-content-between">

            <div v-for="elemento in listaProdotti" class="d-flex align-items-center">
                <div class="me-3 resize">
                    <img :src="elemento.percorso" alt="">
                </div>
                <h5>{{elemento.prodotto}}</h5>
            </div>

        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../styles/general.scss' as *;
.bg-recolor{
    background-color: $dc;
}

h5{
    font-size: 0.9rem;
    color: white;
    margin-bottom: 0;
}

.resize{
    width: 3.4rem;

    .resize:nth-child(4){
        padding: 2rem;
    }
}
</style>