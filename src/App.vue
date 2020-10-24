<template>
  <div id="app">
    <MainPage />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import MainPage from './views/MainPage.vue';

@Component({
  components: {
    MainPage,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  height: 100%;
  color: $color-main;

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
