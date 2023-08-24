<template>

<EventListView/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import EventListView from './views/EventListView.vue'

export default defineComponent({
  name: 'App',
  components: {
    EventListView
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
