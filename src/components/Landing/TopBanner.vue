<script setup>
import BannerClassCard from './BannerClassCard.vue';
import BannerPromotion from './BannerPromotion.vue';

</script>

<template>
<main class="top-banner-container">
    <div class="max-w-6xl mx-auto">
<h1 class="text-white text-5xl font-bold leading-loose">৬ষ্ঠ-এইচএসসি শ্রেণির </h1>
<h1 class="text-white text-5xl font-bold ">অনলাইন ব্যাচে ভর্তি চলছে!</h1>
<p class="text-gray-400 my-4">বছর জুড়ে অভিজ্ঞ শিক্ষকদের সাথে সম্পূর্ণ সিলেবাসের 💯 তে 💯 প্রস্তুতি!</p>
    </div>

    <div>
        <BannerClassCard/>
        <div class="flex gap-1  text-green-300 font-semibold justify-center items-center pt-4">
            <p>অনলাইন ব্যাচ সম্পর্কে আরও জানুন</p>
            <i class="text-xs fa-solid fa-chevron-right"></i>
        </div>
    </div>
    <div>
        <BannerPromotion/>
    </div>
    
    
</main>
</template>


<style>
.top-banner-container{
    background-image: url('https://c0.wallpaperflare.com/preview/864/478/540/brown-book.jpg');
    background-position: center; 
    background-repeat: no-repeat; 
    background-size: cover;
    height: 100%;
    
}

</style>