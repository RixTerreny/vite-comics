<script>
export default{}
</script>

<template>
    <div class="bg-recolor">
        <div class="container p-5 d-flex justify-content-between">
            <div class="d-flex align-items-center">
                <div class="me-3 resize">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                </div>
                <h5>DIGITAL COMICS</h5>
            </div>

            <div class="d-flex align-items-center">
                <div class="me-3 resize">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                </div>
                <h5>DC MERCHANDISE</h5>
            </div>

            <div class="d-flex align-items-center">
                <div class="me-3 resize">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                </div>
                <h5>SUBSCRIPTION</h5>
            </div>

            <div class="d-flex align-items-center">
                <div class="me-3 p-2 resize">
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                </div>
                <h5>COMIC SHOP LOCATOR</h5>
            </div>

            <div class="d-flex align-items-center">
                <div class="me-3 resize">
                    <svg version="1.1" id="Layer_2_1_" xmlns="http://www.w3.org/2000/svg" x="0" y="0" viewBox="0 0 79.5 50.9" xml:space="preserve"><style>.st0{fill:none;stroke:#fff;stroke-width:1.7732;stroke-miterlimit:10}</style><path class="st0" d="M73.9 49.6H5.3c-2.1 0-3.8-1.7-3.8-3.8V5.4c0-2.1 1.7-3.8 3.8-3.8h68.6c2.1 0 3.8 1.7 3.8 3.8v40.3c0 2.1-1.7 3.9-3.8 3.9zM1.5 15.4h76.2"/><path fill="#fff" stroke="#fff" stroke-width=".998" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M50.1 22.1l-9.7 1.4 5.1-16.4L29 30.2l9.3-1.3L34.4 44z"/></svg>
                </div>
                <h5>DC POWER VISA</h5>
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
}
</style>