<template>
  <div id="app">
    <SearchBar @termChange="onTermChange"></SearchBar>
  </div>
</template>

<script>
import SearchBar from './components/SearchBar'
const API_KEY = 'AIzaSyBi-y4K_lHR_gbVZY0CNicyJOla9XlLx3s';

export default {
  name: 'App',
  components: {
    SearchBar
  },
  method: {
    onTermChange(searchTerm) {
      console.log(searchTerm);
    }
  }
};
</script>

<style>

</style>
