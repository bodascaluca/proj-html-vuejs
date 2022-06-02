<template>
  <div class="ms_container">

    <div class="d-flex justify-content-between">

        <div class="image-1 col me-3">
            <img src="../assets/image/social-1.jpg" alt="">
        </div>

        <div class=" image-2 col-6 border ms-1 me-2 text-center padding">
            <h6 class=" text-uppercase mt-5 color-grey mb-3">made for sharing</h6>
            <h4 class="color-primary mb-3"><b>Let's stay in touch</b></h4>
            <button class="btn-prymary ms_btn-qui"><a href="#"> <i class=" a-size fab fa-instagram"></i><span class="ms-3 i-size">Follow Us</span></a></button>
        </div>

        <div class="image-2 col  ms-3">
            <img src="../assets/image/social-2.jpg" alt="">
        </div>

    </div>

    <div class="d-flex justify-content-between mt-4">

        <div class="col me-2">
            <img src="../assets/image/social-3.jpg" alt="">
        </div>

        <div class="color-3 col ms-3 me-3">
            <img src="../assets/image/social-5.jpg" alt="">
        </div>
        
        <div class="color-3 col ms-2 me-3">
            <img src="../assets/image/social-4.jpg" alt="">
        </div>

        <div class="col  ms-2">
            <img src="../assets/image/social-6.jpg" alt="">
        </div>

    </div>

   

  </div>
</template>

<script>
export default {
name:"SectionOtto",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
@import "../style/btn.scss";

.image-2{
    background-color:#f2eef5 ;
}

.color-grey{
    font-size:.7rem;
    color:$color-grey-text;
}

.color-primary{
    font-size:1.9rem;
    color:$brand-primary-color;
}

.ms_btn-qui{
    padding: .5rem 1.5rem;
    border-radius:5px;
    border: 1px solid $background-secondary-color;
}

.padding {
    padding-top:50px;
}
.a-size,
.i-size{
    font-size:.8rem;
}
</style>