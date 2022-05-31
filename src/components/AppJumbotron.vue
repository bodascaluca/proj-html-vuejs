<template>
  <div class="ms_jumbotron  pt-5">
      <div class="ms_container">
          <div class="ms_jumbotron-title col-3 ">
              <h6 class="text-uppercase ms_colorText mb-3">Fresh & tasty bakery every day</h6>
              <h1 class="ms_colorH text-capitalize mb-3">The perfect Fresh Bread</h1>
              <p class="ms_colorText mb-3">Cras consequat lectus vestibulum tortor pulvinar, quis euismod nisl varius. Aliquam erat volutpat. Nullam quis sagittins nibh ac nulla id orci tempor.</p>
              <button class=" ms_colorH">Explore our products</button>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name:"AppJumbotron",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";

.ms_jumbotron{
    height:700px;
    background-image: url(../assets/image/hero-header-bakery.jpg);
    background-position: bottom;
    background-size: cover;

    &-title{
        padding-top:200px;
    }

    h6,
    p{
        font-size: .7rem;
    }

    .ms_colorH{
    color:$brand-primary-color;
    }

    .ms_colorText{
        color:$color-grey-text;
    }
}

</style>