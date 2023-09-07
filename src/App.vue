<template>
  <div id="app" class="p-1">
    <CcvSimpleBarChart :data="data" :options="options" />
  </div>
</template>

<script>
import data from './data.js';
import options from './option.js';

export default {
  data() {
    return {
      data,
      options,
    };
  },
};
</script>

<style>
@import '@carbon/charts-vue/styles.css';
.p-1 {
  padding: 2rem;
}
</style>
