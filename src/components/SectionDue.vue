<template>
  <div class="sectionDue ms_container">
      <div class=" text-center ">
          <h4 class=" mini-title text-uppercase mb-3">corporate & weddings</h4>
          <h3 class=" color-primary text-capitalize mb-4">baking special moments</h3>
      </div>
      <div class=" d-flex mt-2 justify-content-between ">
          <div class="col imageUno me-5"></div>
          <div class="col imageDuo"></div>
      </div>
  </div>
</template>

<script>
export default {
    name:"SectionDue",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";
.sectionDue{

    
    .mini-title{
        color:$color-grey-text;
        font-size:.8rem;
    }
    .color-primary{
        color:$brand-primary-color;
    }

    .imageUno{
        height: 500px;
        background-position: center;
        background-size:cover;
        background-repeat:no-repeat;
        background-image: url("../assets/image/social-1.jpg");
    }
    .imageDuo{
        height: 500px;
        background-position: center;
        background-size:cover;
        background-repeat:no-repeat;
        background-image: url("../assets/image/wedding-bg.jpg");
    }
}

</style>