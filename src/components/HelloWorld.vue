<template>
  <div class="test">
    Woof
  </div>
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'
export default defineComponent({
  name: 'HelloWorld'
})
</script>

<style scoped>
  .test {
    background:
      no-repeat bottom right/166px url("@/static/img/test.png"),
      linear-gradient(45deg, #4978EA 1.56%, #A09FC3 111.41%);
  }
</style>
