<script setup>
import CardSectionCard from './CardSectionCard.vue';
</script>

<template>
    <main class="bg-gray-100">
        <div class="flex items-center flex-col pt-28">
            <h1 class="text-4xl w-96 text-center font-semibold pb-4">নিজের শেখা নিজেই গুছিয়ে নেয়ার যাত্রা শুরু হোক</h1>
            <p class="text-gray-600">যেকোনো বিষয়ে যেকোনো কিছু শিখতে চলে যাও তোমার পছন্দের সেকশনে</p>
        </div>

        <div class="grid grid-cols-2 max-w-6xl mx-auto gap-12 pt-8">
            <CardSectionCard>
                <template #title>
                    ক্লাস ৫-১২ 
                </template>
                <template #avatar>
                    <img class="h-14" src="E:\Vue Templates\10-minute-school\src\assets\Top-banner\school-bag.png" alt="">
                </template>
                <template #description>
                    ফ্রি ভিডিও , লাইভ ক্লাস 
                </template>


                </CardSectionCard>
            <CardSectionCard>
                <template #title>
                    স্কিলস
                </template>
                <template #avatar>
                    <img class="h-14" src="E:\Vue Templates\10-minute-school\src\assets\Top-banner\rocket.png" alt="">
                </template>
                <template #description>
                    ইংলিশ, ফ্রীল্যানসিং, স্কিলস ও আইটি 
                </template>


                </CardSectionCard>
            <CardSectionCard>
                <template #title>
                    ভর্তি পরীক্ষা 
                </template>
                <template #avatar>
                    <img class="h-14" src="E:\Vue Templates\10-minute-school\src\assets\Top-banner\graduate-cap.png" alt="">
                </template>
                <template #description>
                    বিশ্ববিদ্যালয়+ গুচ্ছ , মেডিকেল 
                </template>


                </CardSectionCard>
            <CardSectionCard>
                <template #title>
                    চাকরি প্রস্তুতি 
                </template>
                <template #avatar>
                    <img class="h-14" src="E:\Vue Templates\10-minute-school\src\assets\Top-banner\hand-bag.png" alt="">
                </template>
                <template #description>
                    বিসিএস , ব্যাঙ্ক জবস , সরকারি চাকরি 
                </template>


                </CardSectionCard>
        </div>
        <div class="pt-12 ">
            <img src="https://cdn.10minuteschool.com/images/city_background_1700632037739.png" alt="">
        </div>
    </main>
</template>

<style></style>