<template>
  <div class="d-flex ms_container">

    <div class=" col-7">

      <div class="ms-4 ">
        <img class="image-size" :src="require('../assets/image/' + img.title + '.png')" alt="Bakery Logo">
      </div>

      <div class="misure ms-4 mt-4">
        <ul class="d-flex">

          <li class="nav-item" v-for="(item) in header" :key="item.id">
            <a class="nav-link  color" aria-current="page" href="#">{{item.name }}</a>
          </li>

          <li class="nav-item" v-for="(item, index) in icon" :key="index">
            <a class="nav-link" href="#" aria-disabled="true"><i :class="item.icon"></i> <span class=" circle ms-2">0</span>  </a>
          </li>

        </ul>

        <h6 class="color-grey mt-5 mb-5">
          © Copyright 2012 -2020 | Avada Therm by ThemeFusion | All Rights Reserved | Powered by WordPress
        </h6>
      </div>
    

    </div>

    <div class=" right d-flex  flex-column justify-content-around  align-items-end  col-5">

        <h3 class="color-primary me-5"><b>Suscribe to our Newsletter</b></h3>

        <div class="">
          <input class="input-size w-50" type="email" placeholder="Enter email address*">
          <button class="btn-prymary ms-2 btn-size-right "><a href="#">Subscribe</a></button>
        </div>

        <div class="me-5">
          <ul class="d-flex">
            <li> <a href="#"><i class="me-4 a-size  fab fa-instagram"></i></a> </li>
            <li> <a href="#"><i class="me-4 a-size  fab fa-twitter"></i></a> </li>
            <li> <a href="#"><i class="me-4 a-size  fab fa-facebook-f"></i></a></li>
            <li> <a href="#"><i class=" a-size  fab fa-pinterest-p"></i></a> </li>
          </ul>
        </div>

        <div class="bottom-up">
          <button class="click-up"><a href="#"><i class=" icon-color fas fa-angle-up"></i></a></button>
        </div>
    </div>

  </div>
</template>

<script>
export default {
    name:"AppFooter",
     props:{
      header:Array,
      icon:Array,
      img:Object
    }
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";

ul li {
  list-style-type: none;
}

li a{
  color:inherit;
  color:$brand-primary-color;
}

.image-size{
  width: 130px;
  // font-size:2rem;
}
.misure{
  font-size:.7rem;
}

.circle{
  background-color:#f1edf5;
    display: inline-block;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    text-align: center;
    line-height: 10px;
}

.color-grey{
  color:$color-grey-text;
  font-size:.7rem;
}

.input-size{
  padding: .3rem 1rem;
}

.color-primary{
  font-size:1.2rem;
  color:$brand-primary-color;
}

.btn-size-right {
    border: 1px solid white ;
    border-radius: 10px;
    padding: .4rem 1.4rem;
}

.a-size{
  font-size:.8rem;
}

.right{
  position: relative;
}
.bottom-up{
  position: absolute;
  bottom: 0;
  right:10px;
}

.click-up{
  background-color:#474747;
  padding: .2rem .3rem;
  border-radius: 5px;
}

.icon-color{

  color:white;
}

</style>