<script setup></script>

<template>

<div class="flex justify-between items-center bg-white px-8 py-12 rounded-lg hover:bg-gray-200 duration-500 border-h">
    <div class="flex gap-4">
    <slot name="avatar"></slot>
<div>
    <h1 class="text-2xl font-semibold">
        <slot name="title"></slot>
    </h1>
    <p class="text-gray-400">
        <slot name="description"></slot>
    </p>
</div>

    </div>
    <div>
        <i class="fa-solid fa-chevron-right"></i>
    </div>
</div>
</template>

<style>
.border-h{
    border: 1px solid transparent;
}

.border-h:hover {
    border: 1px solid green;
}
</style>