<template>
  <div class="ms_jumbotron  pt-5">
      <div class="ms_container">
          <div class="ms_jumbotron-title col-4 ">
              <h6 class="text-uppercase ms_colorText mb-3">Fresh & tasty bakery every day</h6>
              <h1 class="ms_colorH text-capitalize mb-3">The perfect Fresh Bread</h1>
              <p class="ms_colorText mb-3">Cras consequat lectus vestibulum tortor pulvinar, quis euismod nisl varius. Aliquam erat volutpat. Nullam quis sagittins nibh ac nulla id orci tempor.</p>
              <button class="ms_btn-style btn-white ms_colorH mt-3"> <span class="btn-tx" >Explore our products</span></button>
        </div>
      </div>
      <div class="demos demos-shop">
          <i class="fas fa-shopping-basket"></i>
          <p>Demos</p>
      </div>
      <div class="demos demos-cash">
          <div class="dollaro" >$</div>
          <b class="number">39</b>
          <p class="demos-tx" >On Sale</p>
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
@import "../style/btn.scss";

.ms_jumbotron{
    height:700px;
    background-image: url(../assets/image/hero-header-bakery.jpg);
    background-position: bottom;
    background-size: cover;

    .ms_container{

        position: relative;
    }

    .demos{
        background-color: white;
        padding: .5rem;
        text-align: center;
        border-radius:4px;
    }
      .demos-shop{
            position: absolute;
            top:130px;
            right: 10px;
            color:#34475b;
        }

        .demos-cash{
            position: absolute;
            top:195px;
            right: 10px;

            .dollaro{
                color:#67bc7c;
                position:absolute;
                top:3px;
                font-size:.8rem;
            }

            .number{
                color:#67bc7c;
                font-size:1.2rem;
            }

            .demos-tx{
                font-size:.6rem;
            }
        }

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