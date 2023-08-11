<script setup>
import { NButton } from 'naive-ui';
</script>

<template>
  <div class="container mx-auto">
    <div class="flex flex-col w-24 mx-auto space-y-1">
      <n-button>Default</n-button>
      <n-button type="tertiary"> Tertiary </n-button>
      <n-button type="primary"> Primary </n-button>
      <n-button type="info"> Info </n-button>
      <n-button type="success"> Success </n-button>
      <n-button type="warning"> Warning </n-button>
      <n-button type="error"> Error </n-button>
    </div>
  </div>
</template>
