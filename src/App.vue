<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-12">
          <h1>Quotes New App</h1>
          <app-quotes></app-quotes>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Quote from "./components/Quote.vue";
export default {
  components: {
    "app-quotes": Quote,
  },
};
</script>

<style></style>
