<script setup></script>

<template>

    <main class="fixed w-full  flex gap-6 py-1 border-b border-gray-200 bg-gray-100 z-10">
        <div class="flex items-center">
            <div><img class="pl-8 pr-3 h-6" src="https://cdn.10minuteschool.com/images/svg/10mslogo-svg.svg?w=100&h=27" alt=""></div>
        </div>
        <div class="relative">
            <input class="border border-gray-300 rounded-2xl w-72 py-2 pl-10 px-1 outline-0" type="text" placeholder="স্কিলস কোর্স, কিংবা স্কুল প্রোগ্রাম সার্চ করুন...">           <div class="absolute search"><i class="fa-solid fa-magnifying-glass"></i></div>
        </div>
            <div class="relative flex items-center class-div">
            <div class="flex items-center gap-2 hover:text-green-500 cursor-pointer ">
                <p>ক্লাস ৫-১২</p>
                <i class="fa-solid fa-chevron-down"></i>
            </div>
            <div class="absolute class-dropdown bg-white px-3 py-4">
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>এইচএসসি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>দশম শ্রেনি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>নবম শ্রেনি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>অষ্টম শ্রেনি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>সপ্তম শ্রেনি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>ষষ্ঠ শ্রেনি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <i class="fa-solid fa-book"></i>
                    <p>পঞ্চম শ্রেনি</p>
                </div>
                
            </div>
        </div>

        <div class="relative flex items-center skill-div ">

            <div class="flex items-center gap-2 hover:text-green-500 cursor-pointer">
                <p>স্কিলস</p>
                <i class="fa-solid fa-chevron-down"></i>
            </div>
            <div class="absolute skill-dropdown bg-white px-4 py-4 rounded-xl">
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\layer.png" alt="">
                    <p>সকল কোর্সসমূহ</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\chat.png" alt="">
                    <p>ভাষা শিক্ষা</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\promotion.png" alt="">
                    <p>ক্যারিয়ার রেডিনেস</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\settings.png" alt="">
                    <p>স্কিলস এন্ড আইটি</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\giftbox.png" alt="">
                    <p>বান্ডেল</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\ruler.png" alt="">
                    <p>ডিজাইন এন্ড ক্রিয়েটিভ</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\children.png" alt="">
                    <p>কিডস কোর্সসমূহ</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\businessman.png" alt="">
                    <p>প্রফেশনাল কোর্সসমূহ</p>
                </div>
                <div class="flex gap-4 items-center py-1.5">
                    <img class="h-6" src="E:\Vue Templates\10-minute-school\src\assets\Skill-section\free.png" alt="">
                    <p>ফ্রি কোর্সসমূহ</p>
                </div>
                
            </div>
        </div>
        <div class="flex items-center hover:text-green-500 cursor-pointer">
            ভর্তি পরীক্ষা
        </div>
        <div class="flex items-center hover:text-green-500 cursor-pointer">
            চাকরি প্রস্তুতি
        </div>
        <div class="flex items-center hover:text-green-500 cursor-pointer">
            অনলাইন ব্যাচ
        </div>
        <div class="text-lg flex items-center gap-1 text-green-400 pl-32">
            <i class="fa-solid fa-phone"></i>
            <p>16910</p>
        </div>
        <div class="flex items-center">
            <button class="bg-green-500 px-4 py-1 text-white font-semibold rounded">লগ-ইন </button>
        </div>
    </main>
</template>


<style>
.search{
    top: 22%;
    left: 5%;
}
.class-div:hover .class-dropdown{
    display: block;

}
.class-dropdown{
    width: 135px;
    top: 84%;
    left: -25%;
    display: none;
    box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px, rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;

}
.skill-div:hover .skill-dropdown{
    display: block;

}
.skill-dropdown{
    width: 210px;
    top: 84%;
    left: -70%;
    display: none;
    box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px, rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;

}
</style>