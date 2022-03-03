<template>
  <nav class="navigation-links3-nav" v-bind:class="rootClassName">
    <router-link to="/about" class="navigation-links3-navlink">
      {{ text }}
    </router-link>
    <router-link to="/features" class="navigation-links3-navlink1">
      {{ text1 }}
    </router-link>
    <router-link to="/invite-bot" class="navigation-links3-navlink2">
      {{ text2 }}
    </router-link>
    <router-link to="/stream" class="navigation-links3-navlink3">
      {{ text3 }}
    </router-link>
    <router-link to="/support" class="navigation-links3-navlink4">
      {{ text4 }}
    </router-link>
  </nav>
</template>

<script>
export default {
  name: 'NavigationLinks3',
  props: {
    text2: {
      type: String,
      default: 'Invite Bot',
    },
    rootClassName: String,
    text: {
      type: String,
      default: 'About',
    },
    text4: {
      type: String,
      default: 'Support',
    },
    text1: {
      type: String,
      default: 'Features',
    },
    text3: {
      type: String,
      default: 'Stream',
    },
  },
}
</script>

<style scoped>
.navigation-links3-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-links3-navlink {
  text-decoration: none;
}
.navigation-links3-navlink1 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links3-navlink2 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links3-navlink3 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}
.navigation-links3-navlink4 {
  margin-left: var(--dl-space-space-twounits);
  text-decoration: none;
}








@media(max-width: 767px) {
  .navigation-links3-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links3-navlink {
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links3-navlink1 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links3-navlink2 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links3-navlink3 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links3-navlink4 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
