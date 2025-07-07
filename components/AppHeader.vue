<template>
  <div class="border-b">
    <UContainer>
      <UHorizontalNavigation :links="links" />
    </UContainer>
  </div>
</template>

<script setup lang="ts">
const links = [
  { label: 'Option 1', to: '/option1' },
  { label: 'Option 2', to: '/option2' },
  { label: 'Option 3', to: '/option3' },
  { label: 'Option 4', to: '/option4' }
]
</script>
