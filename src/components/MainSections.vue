<template>
  <div>

    <div>
      <AppJumbotron />
    </div>

    <div>
      <SectionUno />
    </div>

    <div>
      <SectionDue />
    </div>

    <div>
      <SectionTre />
    </div>

    <div>
      <SectionQuattro />
    </div>

    <div>
      <SectionCinque />
    </div>

    <div>
      <SectionSei />
    </div>
    
     <div>
      <SectionSette />
    </div>

    <div>
      <SectionOtto />
    </div>

     <div>
      <SectionNove />
    </div>

  </div>
</template>

<script>
import AppJumbotron from "./AppJumbotron.vue";
import SectionUno from "./SectionUno.vue";
import SectionDue from "./SectionDue.vue";
import SectionTre from "./SectionTre.vue";
import SectionQuattro from "./SectionQuattro.vue";
import SectionCinque from "./SectionCinque.vue";
import SectionSei from "./SectionSei.vue";
import SectionSette from "./SectionSette.vue";
import SectionOtto from "./SectionOtto.vue";
import SectionNove from "./SectionNove.vue";








export default {
    name:"MainSections",
    components:{
      AppJumbotron,
      SectionUno,
      SectionDue,
      SectionTre,
      SectionQuattro,
      SectionCinque,
      SectionSei,
      SectionSette,
      SectionOtto,
      SectionNove,
    },
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";


</style>