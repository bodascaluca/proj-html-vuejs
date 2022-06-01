<template>
  <div class=" header w-100 d-flex justify-content-between align-items-center">

    <div class="ms-4">
      <img class="w-75" :src="require('../assets/image/' + img.title + '.png')" alt="Bakery Logo">
    </div>
<!-- avada-bakery-logo -->
    <div class="headerMenu"> 
        <nav class="navbar navbar-expand-lg navbar-light">
          <div class="container-fluid">
            <!-- <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button> -->

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            
              <ul  class="navbar-nav me-auto mb-2 mb-lg-0">
              
                <li class="nav-item" v-for="(item, index) in header" :key="index">
                  <a class="nav-link  color" aria-current="page" href="#">{{item.name }}</a>
                </li>

                <li class="nav-item" v-for="(item, index) in icon" :key="index">
                  <a class="nav-link" href="#" aria-disabled="true"><i :class="item.icon"></i></a>
                </li>
           
              </ul>

            </div>
          </div>
      </nav>
    </div>

  </div>
</template>

<script>
export default {
    name:"HeaderFix",
    props:{
      header:Array,
      icon:Array,
      img:Object
    }
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";

.header{
  height:80px;
  // background:#f3e7f1;
  background: $background-header-color;

  .nav-item a{
    // color:#5b2ba2;
    color:$brand-primary-color;
    font-size:.7rem;
  }
}

</style>