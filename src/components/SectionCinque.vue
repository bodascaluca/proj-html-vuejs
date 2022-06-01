<template>
  <div class="ms_container mt-4 d-flex">

        <div class="q q-1 me-2 col">
            <img class="image" src="../assets/image/bakery-process-2.jpg" alt="">
            <div class="title color">
            <h2><b>We Start Baking</b> </h2>
        </div>

        <div class="number color">
          <h2 class="nm-size">02</h2>
        </div>

        <div class="paragrafo color">
          <h6 class="pr-h grey text-uppercase">manual ingredients selection</h6>
          <p class="pr-p mt-3">Cras consequat lectus vestibulum torto pulvinar, quis euismod nisl varius. Ut eu laoreet ex. Aliquam erat volutpat. Nullam quis sagittis nibh. Morbi consectetur ultricies ante ac congue. Donec lorem erat, finibus in velit placerat, rutrum augue.</p>
        </div>

      </div>

      <div class="q q-2 ms-2 col">
          <h6 class="h-1 ms-5 mt-5 text-uppercase color-grey">Dont just take our word for it</h6>
          <h4 class="h-2 ms-5 me-5 mt-4 color-primary"><b> "Finally found an alternative to the mass produced products. Something that incorporates real organic ingredients, nutrient dense wellness whilr promoting sustainability and activity."</b></h4>
          <h6 class="h-3 ms-5 mt-4 text-capitalize color-grey">Rachel Cooper, Founder </h6>
      </div>

  </div>
</template>

<script>
export default {
    name:"SectionCinque",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";

.q{
    position:relative;
}
.q-1{
    color:white;

  .image{
    filter:brightness(0.6);
  }
    .title{
    width:350px;
    position:absolute;
    top:30px;
    left:30px; 
  }

  .number{
    position:absolute;
    top:30px;
    right:30px;

    .nm-size{
      font-size:3rem;
    }
  
    }
     .paragrafo{
    width:200px;
    position:absolute;
    bottom:30px;
    left:30px;

    .grey{
      color:$color-grey-text;
    }
    .pr-h{
      font-size:.6rem;
    }
    .pr-p{
      font-size:.8rem;
    }


  }
}

.q-2{
    background-color: $background-secondary-color;

    .h-1{
        font-size:.7rem;
    }   

    .h-2{
    font-size:2rem;        
    }

    .h-3{
        font-size:.8rem;
    }

    .color-primary{
        color:$brand-primary-color;
    }

    .color-grey{
        color:$color-grey-text;
    }
}
</style>