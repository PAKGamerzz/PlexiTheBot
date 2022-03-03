<template>
  <div class="component-container">
    <img :alt="image_alt" :src="image_src" class="component-image" />
  </div>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {
    image_alt: {
      type: String,
      default: 'image',
    },
    image_src: {
      type: String,
      default: '/playground_assets/3qty-200h.gif',
    },
  },
}
</script>

<style scoped>
.component-container {
  display: flex;
  position: relative;
}
.component-image {
  width: 100px;
  object-fit: cover;
}
</style>
