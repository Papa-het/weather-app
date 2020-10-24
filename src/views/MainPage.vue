<template>
  <div class="main">
    <Sidebar />
    <Board />
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';
import Sidebar from '@/components/Sidebar';
import Board from '@/components/Board';

@Component({
  name: 'MainPage',
  components: {
    Sidebar,
    Board,
  },
})
export default class MainPage extends Vue {}
</script>

<style lang="scss" scoped>
.main {
  height: 100%;

  display: flex;
  flex-direction: column;

  @media (min-width: $middle) {
    display: grid;
    grid-template-columns: 0.4fr 1fr;
  }
}
</style>
