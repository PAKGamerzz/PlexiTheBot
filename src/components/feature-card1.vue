<template>
  <div class="feature-card1-feature-card" v-bind:class="rootClassName">
    <h2 class="feature-card1-text">{{ title }}</h2>
    <img :alt="image_alt" :src="image_src" class="feature-card1-image" />
  </div>
</template>

<script>
export default {
  name: 'FeatureCard1',
  props: {
    image_alt: {
      type: String,
      default: 'Stay',
    },
    rootClassName: String,
    image_src: {
      type: String,
      default:
        '/playground_assets/the_kid_laroi_justin_bieber_stay_music_video-948948477-msmall-200w.jpg',
    },
    title: {
      type: String,
      default: 'Stay - Justin Bieber and Kid Lario',
    },
  },
}
</script>

<style scoped>
.feature-card1-feature-card {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-unit);
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(18, 18, 18, 0.1);
  transition: 0.3s;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.feature-card1-feature-card:hover {
  transform: scale(1.02);
}
.feature-card1-text {
  margin-bottom: var(--dl-space-space-twounits);
}
.feature-card1-image {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-radius4);
}



</style>
