<script setup>
import MainHeader from '@/components/MainHeader.vue';
import TopBanner from '@/components/Landing/TopBanner.vue';
import TopBannerSlider from '@/components/Landing/TopBannerSlider.vue';
import CardSection from '@/components/Landing/CardSection.vue';
import VideoSection from '@/components/Landing/VideoSection.vue';
import LandingPageButton from '@/components/Landing/LandingPageButton.vue';




</script>

<template>
 <main>
  <div>
    <MainHeader/>
  </div>
  <div class="pt-12">
    <TopBanner/>
  </div>
 <div class="bg-black">
  <div class="max-w-6xl mx-auto pb-16">
    <h1 class="text-5xl text-white font-semibold pt-16 pb-4">স্কিল ডেভেলপমেন্টের নির্দিষ্ট কোর্সে দারুণ ছাড়!</h1>
    <p class="text-gray-400 pb-6">পুরো মাস জুড়ে টেন মিনিট স্কুলের নির্দিষ্ট কোর্সসমূহ পেয়ে যান বিশেষ মূল্যে। এবার শেখার শুরু হোক টেন মিনিট স্কুলের সাথে!</p>
    <TopBannerSlider/>
    <div class="flex gap-1  text-green-300 font-semibold justify-center items-center pt-4">
            <p>৩০+ ফ্রি কোর্সে এনরোল হতে ক্লিক করুন</p>
            <i class="text-xs fa-solid fa-chevron-right"></i>
        </div>    

  </div>

</div>
<div>
  <CardSection/>
</div>
<div class="pb-24">
  <VideoSection/>

  <LandingPageButton>
    <div>সকল কোর্স</div>
  </LandingPageButton>
</div>

 </main>
</template>
