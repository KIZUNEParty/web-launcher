<template>
  <div id="app">
    <div class="bg"></div>

        <Nav />
        <PDevider />

        <div class="centerize">
            <h1>
                <VueClock :isMinute="true" :isSecond="true" />
            </h1>
        </div>
    </div>
</template>

<style>
@import url(./style/main.css);
@import url(./style/nav.css);
@import url(./style/index.css);
</style>

<script>
import Vue from 'vue'
import VueClock from '@dangvanthanh/vue-clock'

Vue.component('VueClock', VueClock)

export default {
  components: { VueClock },
}
</script>