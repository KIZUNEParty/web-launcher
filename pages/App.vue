<template>
  <div id="app">
      <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
      </head>
      <div class="bg"></div>
      
      <Nav />
      <PDevider />

      <center>
        <div class="parting">
          <div class="row">
            <div class="col-3">
              <a href="https://detzz.in.th" target="_blank">
                <imgHome />
                <span>
                  Home
                </span>
              </a>
            </div>
            <div class="col-3">
              <a href="https://myanimelist.net/profile/detzz" target="_blank">
                <imgMAL />
                <span>
                  MyAnimeList
                </span>
              </a>
            </div>
            <div class="col-3">
              <a href="https://anilist.co/user/detzz" target="_blank">
                <imgAni />
                <span>
                  Anilist
                </span>
              </a>
            </div>
            <div class="col-3">
              <a href="https://animemusicquiz.com/" target="_blank">
                <imgAMQ />
                <span>
                  AMQ
                </span>
              </a>
            </div>
            <div class="col-3">
              <a href="https://detzz.in.th/Donate" target="_blank">
                <imgHome />
                <span>
                  Donation
                </span>
              </a>
            </div>
          </div>
        </div>
      </center>
  </div>
</template>

<style>
@import url(./style/main.css);
@import url(./style/nav.css);
@import url(./style/app.css);
</style>