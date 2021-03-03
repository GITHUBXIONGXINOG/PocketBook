<template>
 <div class="nav">
   <init-panel />
 </div>
 
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import initPanel from './components/initPanel.vue'
export default defineComponent({
  name: 'App',
  props: {
    
  },
  components:{
    initPanel
  }
});
</script>
<style lang="scss">
 
</style>
