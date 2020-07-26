<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-12">
          <h1>Quotes New App</h1>
          <app-quote >
            <h1>HI BRO</h1>
            <p>An Amazing Quote!</p>
          </app-quote>
          <hr />
         
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Quote from "./components/Quote.vue";
export default {
  
  components: {
    "app-quote": Quote,
  },
};
</script>

<style>
body {
  background-image: linear-gradient(to left, #fffefe, #0494b8);
}
</style>
