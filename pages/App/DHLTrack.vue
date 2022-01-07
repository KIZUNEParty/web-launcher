<template>
  <div id="app">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>

    <div class="bg"></div>
      
    <Nav />
    <PDevider />

    <div class="centerize">
      <center>
        <div class="container">
          <div class="dhl">
            <div class="ibox" v-if="$route.query.track != null">
              <iframe :src="'https://cdn2.000198.xyz/dhl/?track=' + $route.query.track" frameborder="0"></iframe>
            </div>
            <div class="searchbox centerize" v-else>
              <form action="./DHLTrack/" class="searchForm">
                <input type="text" name="track" placeholder="Tracking No">
                <br />
                <br />
                <button type="submit" class="btn btn-primary">
                  Check!
                </button>
              </form>
            </div>
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