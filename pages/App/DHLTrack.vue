<template>
  <div id="app">
      <div class="bg"></div>
      
      <Nav />
      <PDevider />

      <div class="centerize">
        <center>
          <div class="container">
            <div class="dhl">
              <iframe :src="'https://cdn2.000198.xyz/dhl/?track=' + $route.query.track" frameborder="0"></iframe>
            </div>
          </div>
        </center>
      </div>
  </div>
</template>

<style>
@import url(../style/main.css);
@import url(../style/nav.css);
@import url(../style/dhl.css);
</style>

<script>
  export default {

  }
</script>