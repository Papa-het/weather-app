<template>
  <div class="board">
    board
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'BoardComponent',
})
export default class Board extends Vue {}
</script>

<style lang="scss" scoped>
.board {
  background: #100e1d;
}
</style>
