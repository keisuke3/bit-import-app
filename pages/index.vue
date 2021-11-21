<template>
  <Hello />
</template>

<script lang="ts">
import Vue from 'vue'
import Hello from '@bit/keisuke3.bit-export-app.hello';

export default Vue.extend({
  components: {
    Hello,
  },
});
</script>
