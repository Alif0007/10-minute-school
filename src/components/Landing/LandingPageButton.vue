<script setup></script>

<template>

  <div class="flex justify-center mt-8">
    <button class="button-container relative flex items-center justify-center text-white bg-green-500 hover:bg-green-600 pl-6 pr-12 py-2 rounded">
        <p class="">
            <slot></slot> </p>
       <div class="arrow-right">
        <i class="text-xs  fa-solid fa-chevron-right"></i>
       </div>
    </button>
  </div>
</template>

<style scoped>
.arrow-right{
    position: absolute;
    top: 19%;
    left: 72%;
    transition: 0.35s;
    
}

.button-container:hover .arrow-right{
    left: 78%;

}

.button-container{
    transition: 0.35s;
}


</style>