<template>
  <div class="pt-5">
      <div class="ms_container">

        <img class="image" src="../assets/image/bakery-process-1.jpg" alt="">

        <div class="title color z">
          <h2><b>Tell us what you have in mind</b> </h2>
        </div>

        <div class="number color z">
          <h2 class="nm-size">01</h2>
        </div>

        <div class="paragrafo color z">
          <h6 class="pr-h grey text-uppercase">manual ingredients selection</h6>
          <p class="pr-p mt-3">Cras consequat lectus vestibulum torto pulvinar, quis euismod nisl varius. Ut eu laoreet ex. Aliquam erat volutpat. Nullam quis sagittis nibh. Morbi consectetur ultricies ante ac congue. Donec lorem erat, finibus in velit placerat, rutrum augue.</p>
        </div>
        
      </div>
  </div>
</template>

<script>
export default {
    name:"SectionQuattro",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/btn.scss";

.ms_container{
  position:relative;
  .image{
    filter: brightness(0.6);
  }

  .color{
    color:$color-text;
  }

  .title{
    width:350px;
    position:absolute;
    top:50px;
    left:50px; 
  }

  .number{
    position:absolute;
    top:50px;
    right:50px;

    .nm-size{
      font-size:3.3rem;
    }
  }

  .paragrafo{
    width:400px;
    position:absolute;
    bottom:50px;
    right:50px;

    .grey{
      color:$color-grey-text;
    }
    .pr-h{
      font-size:.7rem;
    }
    .pr-p{
      font-size:1rem;
    }


  }
}


</style>