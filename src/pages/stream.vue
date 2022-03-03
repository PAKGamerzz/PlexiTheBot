<template>
  <div class="stream-container"></div>
</template>

<script>
export default {
  name: 'Stream',
  metaInfo: {
    title: 'Stream - New Project',
    meta: [
      {
        property: 'og:title',
        content: 'Stream - New Project',
      },
    ],
  },
}
</script>

<style scoped>
.stream-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
</style>
