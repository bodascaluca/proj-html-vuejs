<template>
  <div id="app">

    <div class="header border ">
      <HeaderFix :header="header" :icon="icon" :img="img" />
    </div>

    <div class="main">
      <MainSections />
    </div>

    <div>
      <AppFooter />
    </div>

  </div>
</template>

<script>
import HeaderFix from "./components/HeaderFix.vue";
import MainSections from "./components/MainSections.vue";
import AppFooter from "./components/AppFooter.vue";


export default {
  name: 'App',
  components: {
    HeaderFix,
    MainSections,
    AppFooter,
  },
   data: function(){
      return { 
        header:[
          {
            name:"Home",
            id:1,
          },
          {
            name:"Shop",
            id:2,
          },
          {
            name:"About",
            id:3,
          },
          {
            name:"Gallery",
            id:4,
          },
          {
            name:"Locations",
            id:5,
          },
          {
            name:"Journal",
            id:6,
          },
          {
            name:"Contact",
            id:7,
          },
          {
            name:"My Account",
            id:8,
          },
        ],
        icon:[{
          icon:"fas fa-shopping-cart",
        }],
        img:{
          title:"avada-bakery-logo",
        }
      }
    }
      // fas fa-shopping-cart 
}
</script>

<style lang="scss">
@import "./style/common.scss";
@import'~@fortawesome/fontawesome-free/css/all.min.css';
@import "~bootstrap/scss/bootstrap.scss";
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@100;300;400&family=Source+Serif+Pro:wght@400;600&display=swap');

#app {
  font-family: 'Tiro Tamil', serif;
}

.header{
  height: 80px;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 999;
}

</style>
