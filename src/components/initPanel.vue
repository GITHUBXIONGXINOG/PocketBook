<template>
  <div class="initPanel">
    <h2 class="title">请选择CSV文件</h2>
    <input type="file">
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'initPanel',
  props: {
    // msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
 .initPanel {
   
 } 
</style>
