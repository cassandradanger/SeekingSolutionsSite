<template>
  <div id="app">
    <div class="headerThing">
      <img class="logo" src="./assets/SSlogoWhite.png"/>
    </div>
    <router-view/>
    <div class="footerThing">
      <img class="logoFooter" src="./assets/navigating.png"/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}

.headerThing{
  padding: 20px;
  height: 100px;
  width: 100%;
  position: absolute;
  left: 0;
  top: 0;
  color: white;
  background-color: #22622e;
}

.footerThing{
  padding: 20px;
  height: 50px;
  width: 100%;
  position: absolute;
  bottom: 0;
  left: 0;
  color: white;
  background-color: #22622e;
}

.logo{
  height: 100px;
  margin-left: 40px;
}

.logoFooter{
  position: absolute;
  right: 50px;
  bottom: 20px;
  height: 50px;
}

</style>
