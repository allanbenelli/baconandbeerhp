<template>
  <div id="app" class="w-100 h-100">
    <div class="bg-white h-50" style="min-height: 400px">
      <img alt="Bacon and Beer Logo" class="w-50" src="./assets/logo.png" style="margin-top: 100px">
    </div>
    <div style="background-color: black; height: 400px" >
        <a href="mailto:info@baconandbeer.ch" class="h-100 d-flex flex-row justify-content-center align-items-center">
          <div class="w-100 justify-content-between align-items-center flex-row">
            <h1 class="text-white">CONTACT US!</h1>
            <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" fill="white" class="bi bi-envelope" viewBox="0 0 16 16">
              <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
            </svg>
          </div>

        </a>


    </div>
    <div class="bg-white h-50">
      <img alt="Bacon and Beer Portrait" class="w-50" src="./assets/Portrait-BaconandBeer.jpg">
    </div>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
</style>
