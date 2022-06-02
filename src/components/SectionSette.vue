<template>
  <div class="ms_container mt-5 mb-5 pb-5">

      <div class="text-center mb-4">
          <h6 class="h6-title color-grey text-uppercase mb-3">Locations</h6>
          <h4 class="h4-title color-primary"><b>Visit our Bakeries</b></h4>
      </div>

      <div class="d-flex">

          <div class="col border cl-NY">
              <img src="../assets/image/new-york-bk.jpg" alt="">
              
              <div class="">
                  <h3 class="h3-mini-t color-primary text-center mt-4 mb-3"><b>New York</b></h3>
              </div>

              <div class="d-flex justify-content-around align-items-center mb-3">
                  
                  <div class="text-center">
                    <h6 class="h6-title color-grey text-uppercase mb-2">Call us</h6>
                    <p class="p-mini color-grey">1.800.458.556</p>
                  </div>

                  <div class="text-center">
                    <h6 class="h6-title color-grey text-uppercase mb-2">open all week</h6>
                    <p class="p-mini color-grey">9:00 AM - 6:00 PM</p>
                  </div>

                  <div class="btn-size">
                      <button class="btn-white ms_btn-style"><a href="#">View Map</a></button>
                  </div>

              </div>

          </div>

          <div class="col border cl-L">
              <img src="../assets/image/london-bk.jpg" alt="">
              
              <div class="">
                  <h3 class="h3-mini-t color-primary text-center mt-4 mb-3"><b>London</b></h3>
              </div>

               <div class="d-flex justify-content-around align-items-center mb-3">
                  
                  <div class="text-center">
                    <h6 class="h6-title color-grey text-uppercase mb-2">Call us</h6>
                    <p class="p-mini color-grey">1.800.458.556</p>
                  </div>

                  <div class="text-center">
                    <h6 class="h6-title color-grey text-uppercase mb-2">open all week</h6>
                    <p class="p-mini color-grey">9:00 AM - 6:00 PM</p>
                  </div>

                  <div class="btn-size">
                      <button class="btn-white ms_btn-style"><a href="#">View Map</a></button>
                  </div>

              </div>

          </div>

      </div>

  </div>
</template>

<script>
export default {
    name:"SectionSette",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";

.h6-title{
    font-size:.6rem;
}

.h4-title{
    font-size:1.3rem;
}

.color-grey{
    color:$color-grey-text;
}

.color-primary{
    color:$brand-primary-color;   
}

.cl-NY{
    background-color: #f0fafb;
}

.cl-L{
    background-color: #fbf3e4;
}

.h3-mini-t{
    font-size:1.3rem;
}

.p-mini{
    font-size:.8rem;
}

.btn-size{
    font-size:.6rem;
}
</style>