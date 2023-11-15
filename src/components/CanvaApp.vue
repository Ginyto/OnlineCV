<template>

    <iframe  v-show="source.length > 0" loading="lazy" :src="source + '?embed'" allowfullscreen="allowfullscreen" allow="fullscreen" class=" w-full h-full border-none rounded-xl" >
    </iframe>
  

</template>

<script setup>

import { ref } from 'vue'

defineProps({
  source: {
    type: String,
    required: true,
    default: ""
  },
})


</script>

