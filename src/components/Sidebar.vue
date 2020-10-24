<template>
  <div class="sidebar">
    sidebar
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'SidebarComponent',
})
export default class Sidebar extends Vue {}
</script>

<style lang="scss" scoped>
.sidebar {
  background: #1e213a;
}
</style>
