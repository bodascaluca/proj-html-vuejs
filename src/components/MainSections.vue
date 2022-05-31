<template>
  <div>

    <div>
      <AppJumbotron />
    </div>

    <div>
      <SectionUno />
    </div>

  </div>
</template>

<script>
import AppJumbotron from "./AppJumbotron.vue";
import SectionUno from "./SectionUno.vue";


export default {
    name:"MainSections",
    components:{
      AppJumbotron,
      SectionUno
    }
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";


</style>