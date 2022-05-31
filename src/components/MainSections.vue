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

  </div>
</template>

<script>
import AppJumbotron from "./AppJumbotron.vue";
import SectionUno from "./SectionUno.vue";
import SectionDue from "./SectionDue.vue";
import SectionTre from "./SectionTre.vue";



export default {
    name:"MainSections",
    components:{
      AppJumbotron,
      SectionUno,
      SectionDue,
      SectionTre,
    }
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";


</style>