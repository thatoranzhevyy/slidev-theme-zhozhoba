<script setup>
import {defineProps} from 'vue'

const props = defineProps({
  image: {
    type: String,
  }
})
</script>
<template>
  <div class="slidev-layout image">

    <img class="image" :src="props.image">
    <div class="pl-40 my-auto w-full block">
      <slot/>
    </div>
  </div>
</template>
