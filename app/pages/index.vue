<template>
  <UContainer class="page-container">
    <h1 class="title">Nuxt Chat</h1>
    <UButton to="/chat" class="button"> Start Chat </UButton>
  </UContainer>
</template>

<style scoped>
.page-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  /* Removed fixed height to keep header visible */
  padding-top: 2rem;
}

.title {
  font-size: 2.25rem;
  font-weight: bold;
}

.button {
  margin-top: 1rem;
}
</style>
