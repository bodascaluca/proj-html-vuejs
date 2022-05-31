<template>
  <div id="app">

    <div class="header border ">
      <HeaderFix />
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
  }

}
</script>

<style lang="scss">
@import "./style/common.scss";
@import'~@fortawesome/fontawesome-free/css/all.min.css';
@import "~bootstrap/scss/bootstrap.scss";

.header{
  height: 80px;
  position: fixed;
  top: 0;
  left: 0;
}

</style>
