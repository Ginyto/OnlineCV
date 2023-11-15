<script setup>

import { ref } from 'vue'
import CanvaApp from './CanvaApp.vue';



</script>

<template>

  <div class=" min-h-screen w-screen flex flex-wrap justify-between">

    <div class=" flex flex-col">
    <div class=" text-5xl text-white font-extrabold">Gianlucca Annichiarico</div>
      <CanvaApp :source="'https://www.canva.com/design/DAF0OpYEc9M/view'"/>
    </div>

    <div class=" flex flex-col ">
      <h1 class=" flex w-full justify-center p-2">
        <div class=" text-2xl text-white font-extrabold">Projects</div>
      </h1>
      
      <div class=" flex flex-wrap overflow-auto h-full">
        <CanvaApp class=" " :source="'https://www.canva.com/design/DAF0Omo527I/view'"/>
        <CanvaApp class=" " :source="'https://www.canva.com/design/DAF0O9Tw2Ig/view'"/>
        <CanvaApp class=" " :source="'https://www.canva.com/design/DAF0OjdF62s/view'"/>
      </div>
      
    </div>
  
  </div>
  
</template>
