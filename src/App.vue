<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  name: 'AppPrincipale',
  data() {
    return {

    }
  },
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <AppTitle />
  <AppHero>

  </AppHero>
</template>

<style scoped></style>
