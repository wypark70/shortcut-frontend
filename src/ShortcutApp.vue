<template>
  <v-app>
    <v-main>
      <Shortcut></Shortcut>
    </v-main>
  </v-app>
</template>

<script>
import Shortcut from './components/shortcut/Shortcut.vue';

export default {
  name: 'App',

  components: {
    Shortcut,
  },

  data: () => ({
    //
  }),
};
</script>
