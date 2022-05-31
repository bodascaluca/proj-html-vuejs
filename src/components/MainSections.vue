<template>
  <div>
    <div>
      <AppJumbotron />
    </div>
  </div>
</template>

<script>
import AppJumbotron from "./AppJumbotron.vue";

export default {
    name:"MainSections",
    components:{
      AppJumbotron,
    }
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";


</style>