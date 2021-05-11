<script setup>
import {defineProps} from 'vue'

const props = defineProps({
  company: {
    type: String,
  },
  date: {
    type: String,
  },
})
</script>
<template>
  <div class="slidev-layout cover">
    <div v-if="company" class="company-block">
      <span class="logo"></span>
      <span class="pl-6 company">
        {{ company }}
      </span>
    </div>
    <div class="my-auto w-full">
      <div class="block">
        <slot/>
        <div v-if="date" class="pt-24">
          <span class="date">
            {{ date }}
          </span>
        </div>
      </div>
    </div>
  </div>
</template>
