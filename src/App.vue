<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <TitleBar/>
    <Futures/>
    <Theme/>
    <Sponsor/>
    <Footer/>
  </div>
</template>
<script>
import TitleBar from './components/TitleBar'
import Futures from './components/Futures'
import Theme from './components/Theme'
import Sponsor from './components/Sponsor'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    TitleBar,
    Futures,
    Theme,
    Sponsor,
    Footer
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0
}
::-webkit-scrollbar {
  width: 12px;
}
::-webkit-scrollbar-track {
  background: #f1f1f1;
}
::-webkit-scrollbar-thumb {
  background: #b9b9b9;
}
::-webkit-scrollbar-thumb:hover {
  background: #666;
}
body {
  font-family: 'Nunito', sans-serif;
}

</style>
