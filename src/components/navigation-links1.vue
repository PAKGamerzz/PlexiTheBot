<template>
  <nav class="navigation-links1-nav" v-bind:class="rootClassName">
    <router-link to="/about" class="navigation-links1-navlink">
      {{ text }}
    </router-link>
    <router-link to="/features" class="navigation-links1-navlink1">
      {{ text1 }}
    </router-link>
    <router-link to="/invite-bot" class="navigation-links1-navlink2">
      {{ text2 }}
    </router-link>
    <router-link to="/stream" class="navigation-links1-navlink3">
      {{ text3 }}
    </router-link>
    <router-link to="/support" class="navigation-links1-navlink4">
      {{ text4 }}
    </router-link>
  </nav>
</template>

<script>
export default {
  name: 'NavigationLinks1',
  props: {
    text1: {
      type: String,
      default: 'Features',
    },
    text: {
      type: String,
      default: 'About',
    },
    text2: {
      type: String,
      default: 'Invite Bot',
    },
    text3: {
      type: String,
      default: 'Stream',
    },
    rootClassName: String,
    text4: {
      type: String,
      default: 'Support',
    },
  },
}
</script>

<style scoped>
.navigation-links1-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-links1-navlink {
  text-decoration: none;
}
.navigation-links1-navlink1 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links1-navlink2 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links1-navlink3 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links1-navlink4 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}














@media(max-width: 767px) {
  .navigation-links1-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links1-navlink {
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links1-navlink1 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links1-navlink2 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links1-navlink3 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links1-navlink4 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
