<template>
  <div class="d-flex ms_container">

    <div class="border col-8">

      <div class="ms-4">
        <img class="w-25" :src="require('../assets/image/' + img.title + '.png')" alt="Bakery Logo">
      </div>

      <li class="nav-item" v-for="(item) in header" :key="item.id">
        <a class="nav-link  color" aria-current="page" href="#">{{item.name }}</a>
      </li>

      <li class="nav-item" v-for="(item, index) in icon" :key="index">
        <a class="nav-link" href="#" aria-disabled="true"><i :class="item.icon"></i></a>
      </li>

    </div>

    <div class="border col-4">
      njnjn
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


</style>