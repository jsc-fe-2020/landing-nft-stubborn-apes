<template>
    <div id="faq">
        <div class="container py-5">
            <div class="text-center mb-5">
                <h1 class="text-primary text-heading">Frequently Asked Questions</h1>
            </div>
            <div class="row ">
                <div class="col-12 col-md-6 p-2" v-for="item in faq" :key="item">
                     <div class="card card-dark">
                         <div class="card-body ">
                             <button class="btn text-white d-flex justify-content-between align-items-center toggle-faq" >
                                 <div class="text-left px-2">{{item}}</div>
                                 <div>
                                    <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" viewBox="0 0 24 24" style="width: 1.5rem; height: 1.5rem;">
                                        <g fill="none" stroke="currentColor" stroke-width="2">
                                            <circle cx="12" cy="12" r="10"/>
                                            <path stroke-linecap="round" stroke-linejoin="round" d="m8 10.5 4 4 4-4"/>
                                        </g>
                                    </svg>
                                 </div>
                             </button>
                         </div>
                     </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>

const faq = [
    "How much is a Stubborn Ape?", 
    "Are there any Secondary Sale Royalties?",
    "Where can I view my Stubborn Ape NFTS?",
    "What is the Total Supply?",
    "When can we mint the Stubborn Ape Society Collection?",
    "What Blockchain will this be launched on?",
    "What Can I do with my Stubborn Ape?",
    "When will we be able to see rarity and where?"
]
</script>
<style scoped>

#faq{
    min-height: 50vh;
    background-color: black;
}

.text-heading{
    font-family: 'Audiowide', cursive;
    font-size: 1.8rem;
}

.card-dark{
    border: 1px solid #918989;
    background-color: #111111;
    border-radius: 0.4rem;
}

.toggle-faq{
    width: 100%;
}
</style>