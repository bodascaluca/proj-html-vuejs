<template>
  <div class="ms_container mt-4">
      <img class="image" src="../assets/image/bakery-process-3.jpg" alt="">

       <div class="title color z">
          <h2><b>Delivered to your home</b> </h2>
        </div>

        <div class="number color z">
          <h2 class="nm-size">03</h2>
        </div>

        <div class="paragrafo color z">
          <h6 class="pr-h grey text-uppercase">baked to order & gift wrapped</h6>
          <p class="pr-p mt-3">Cras consequat lectus vestibulum torto pulvinar, quis euismod nisl varius. Ut eu laoreet ex. Aliquam erat volutpat. Nullam quis sagittis nibh. Morbi consectetur ultricies ante ac congue. Donec lorem erat, finibus in velit placerat, rutrum augue.</p>
        </div>
        
  </div>
</template>

<script>
export default {
    name:"SectionSei",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";

.image{
    filter:brightness(0.6);
}

.ms_container{
  position:relative;

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
    left:50px;

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