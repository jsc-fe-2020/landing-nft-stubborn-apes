<template>
    <div class="banner d-flex justify-content-center align-items-center">
        <div class="container text-center">
            <div>
                <h1 class="text-primary text-heading">Welcome to the <br> Stubborn Ape Society</h1>
                <p class="text-white">The Stubborn Ape Society is a collection of 7,000 Unique Stubborn Ape NFT’s</p>
            </div>
            <div class="d-flex flex-column justify-content-center align-items-center py-2">
                <h1 class="text-white text-heading-promo">PUBLIC SALE LIVE</h1>
                <div class="d-flex">
                    <button type="button" class="btn btn-transparent text-xl px-4 py-2">View on Opensea</button>
                    <button type="button" class="btn btn-primary text-xl ml-2 px-4 py-2">Mint Now</button>
                </div>
            </div>
        </div>
    </div>
</template>
<style  scoped>
.banner{
    margin-top: -1rem;
    min-height: 80vh;
    background-image:url('../../assets/banner-header.png') ;
    background-repeat: repeat-y;
}
.text-heading{
    font-size: 3rem;
    font-family: 'Audiowide', cursive;
}
.text-heading-promo{
    margin-top: 3rem;
    margin-bottom: 1rem;
    font-size: 3rem;
    font-family: 'Audiowide', cursive;
}
.text-xl{
    font-size: 1.4rem;
}
.btn-transparent{
    background-color: rgba(253, 253, 253, 0.569);
    color: white;
}

@media only screen and (max-width: 420px) {
  .text-heading{
      font-size: 1.8rem;
  }
  .text-heading-promo{
      font-size: 1.8rem;
  }
}
</style>