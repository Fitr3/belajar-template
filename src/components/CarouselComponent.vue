<script setup>

import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://cf.bstatic.com/xdata/images/hotel/max1024x768/329154960.jpg?k=fbf62ccd745e71f122cdab8e02aeedcb12695050a8cdcfff0a9ac07f0de37f78&o=&hp=1',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://arsitagx-master-article.s3.ap-southeast-1.amazonaws.com/article-photo/1006/taman-bali-cover.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://www.kcjlandscaping.ae/wp-content/uploads/2020/10/Villa-landscaping-in-Dubai.jpg',
    'alt': 'Picture 3',
  },

]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>

