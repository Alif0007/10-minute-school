<template>
    <Carousel v-bind="settings" :breakpoints="breakpoints">
      <Slide v-for="slide in slideImages" :key="slideImages">
        <div class="carousel__item"><img  :src=slide alt="" class="rounded-lg"></div>
      </Slide>
  
      <template #addons>
        <Navigation />
      </template>
    </Carousel>
  </template>
  
  <script>
  import { defineComponent } from 'vue'
  import { Carousel, Navigation, Slide } from 'vue3-carousel'
  
  import 'vue3-carousel/dist/carousel.css'
  
  export default defineComponent({
    name: 'Breakpoints',
    components: {
      Carousel,
      Slide,
      Navigation,
    },
    data: () => ({
        slideImages:[
            'https://cdn.10ms.com/builder/sections/resources/images/Free_Carousel_1706596353081.jpg?w=188&h=259',
            'https://cdn.10minuteschool.com/images/gbeg_1700654847504.jpg?w=188&h=259',
            'https://cdn.10ms.com/builder/sections/resources/images/Web-Caeousel_1707643016206.jpg?w=188&h=259',
            'https://cdn.10minuteschool.com/images/spoken_english_1700654322558.jpg?w=188&h=259',
            'https://cdn.10minuteschool.com/images/ielts_1700654663556.png?w=188&h=259',
            'https://cdn.10minuteschool.com/images/emkf_1700654930098.jpg?w=188&h=259',
            'https://cdn.10minuteschool.com/images/facebook_marketing_1700654446863.jpg?w=188&h=259',
            'https://cdn.10minuteschool.com/images/cmtk_1700654766847.jpg?w=188&h=259',
            'https://cdn.10minuteschool.com/images/gbf_1700654530607.jpg?w=188&h=259',
            
        ],
      // carousel settings
      settings: {
        itemsToShow: 1,
        snapAlign: 'center',
        
      },
      // breakpoints are mobile first
      // any settings not specified will fallback to the carousel settings
      breakpoints: {
        // 700px and up
        700: {
          itemsToShow: 3.5,
          snapAlign: 'center',
        },
        // 1024 and up
        1024: {
          itemsToShow: 5.5,
          snapAlign: 'start',
        },
      },
    }),
  })
  </script>
  