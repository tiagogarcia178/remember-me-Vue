<template>
<!-- this component is registered globally to use everywhere -->
  <div>
      <slot></slot> <!-- slot recives HTML, from when this component is used -->
  </div>
</template>

<style scoped>
div {
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  padding: 1rem;
  margin: 2rem auto;
  max-width: 40rem;
}
</style>



