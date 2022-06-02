<template>

     <div class="ms_jumbotron  pt-5 mt-5 mb-5">
      <div class="ms_container ps-5">
          <div class="ms_jumbotron-title col-5 ms-5 ">
              <h6 class="text-uppercase ms_colorText mb-3">Try our seasonal products</h6>
              <h1 class="ms_color-white mb-3"> <b>Order for pick-up or delivery to your home</b> </h1>
              <button class="btn-white ms_colorH mt-3 mb-5"> <span class="btn-tx" >Shop Now</span></button>
        </div>
      </div>

  </div>

</template>

<script>
export default {
    name:"SectionNove",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";

.ms_jumbotron{
    background-image: url(../assets/image/call-to-action-bg.jpg);
    background-position: bottom;
    background-size: cover;

        .ms_container{
            position: relative;
        }
    }

    h6,
    p{
        font-size: .7rem;
    }

    .ms_color-white{
        color:white;
        font-size:1.6rem;
    }
    .ms_colorH{
    color:$brand-primary-color;
    padding:.5rem 1.7rem;
    border-radius:6px;
    border:1px solid white;
    }

    .ms_colorText{
        color:$color-grey-text;
        font-size:.6rem;
    }

</style>