<script>
import AppTitle from './components/AppTitle.vue';
import AppJumbotron from './components/AppJumbotron.vue';

export default {
  data() {
    return {

    }
  },
  components: { AppTitle, AppJumbotron }
}
</script>

<template>
  <!-- header -->
  <AppTitle />
  <!-- jumbotron -->
  <AppJumbotron />
</template>