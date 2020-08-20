<template>
  <div id="app">
    <div class="app-container">
      <!--Header-->
    <Header/>
    

    <!--Nav Bar-->
    <Navbar/>
    <!--Headingtext component-->
    <Headingtext msg1 = "Roof inspections made remote and easy"/>
    <Headingtext msg2 = "Get your roof inspected remotely and connect with our trusted roofers"/>

    <!--Search Bar with auto completion-->
    <Search/>
    <Jumbertron/>

    </div>
  
    
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Navbar from './components/Navbar';
import Headingtext from './components/Headingtext';
import Search from './components/Search'
import Jumbertron from './components/Jumbertron'

export default {
  name: 'App',
  components: {
    Header, Navbar, Headingtext, Search, Jumbertron
  }
   
}

</script>

<style>
#app {
 background-color: gray;
 /* background-image: url(./assets/background.png);
    background-position: 0px 0px;
    background-size: cover; */
 /* font-family: sans-air; */
 max-width: auto;
 max-height:500px;
 }

.app-container{
  box-sizing: border-box;
  padding: 20px 10px;
  margin-left: auto;
  margin-right: auto;
  max-width: 728px;
 
  
}
/* 
@font-face {
  font-family: "sans-air";
  src:url(./assets/fonts/AirbnbCerealBlack.ttf) format("truetype"),url(./assets/fonts/AirbnbCerealBold.ttf) format("truetype"),
  url(./assets/fonts/AirbnbCerealBook.ttf) format("truetype"),url(./assets/fonts/AirbnbCerealExtraBold.ttf) format("truetype"),
  url(./assets/fonts/AirbnbCerealLight.ttf) format("truetype"),url(./assets/fonts/AirbnbCerealMedium.ttf) format("truetype");
} */
</style>

