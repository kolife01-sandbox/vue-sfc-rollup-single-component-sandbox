<script lang="ts">
import Vue from 'vue';
import MyComponent from '@/my-component.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    MyComponent
  }
});
</script>

<template>
  <div id="app">
    <my-component />
  </div>
</template>
