<template>
  <div>
    <job-toolbar></job-toolbar>
  </div>
</template>

<script>
import Vue from 'vue';
import JobToolbar from './JobToolbar.vue';
export default {
  name: 'job',
  components: {
    JobToolbar
  }
}
</script>