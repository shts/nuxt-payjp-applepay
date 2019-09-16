<template>
  <div>
    <a href="/pay.html">ここから Apple Pay</a>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component
export default class index extends Vue {
}
</script>

<style scoped>
  div {
    min-height: 100vh;
    text-align: center;
  }
  a {
    font-size: 36px;
  }
</style>
