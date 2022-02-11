<template>
  <div>
    <app-bar title="平安成电智慧通行" />
    <div class="spinner">
      <md-progress-spinner
        class="md-primary"
        :md-stroke="4"
        :md-diameter="50"
        md-mode="indeterminate"
      />
    </div>
  </div>
</template>

<script>
import AppBar from './AppBar.vue'

export default {
  name: 'PassRulePage',
  components: {
    AppBar
  },
}
</script>

<style lang="less" scoped>
.spinner {
  display: flex;
  justify-content: center;
  padding: 100px;
}
</style>