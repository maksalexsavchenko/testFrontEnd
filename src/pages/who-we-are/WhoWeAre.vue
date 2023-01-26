<template>
  <div class="who-we-are">
    <hero-block/>
    <features-block/>
  </div>
</template>

<script>
import HeroBlock from "@/pages/who-we-are/partials/HeroBlock.vue";
import FeaturesBlock from "@/pages/who-we-are/partials/FeaturesBlock";

export default {
  name: "WhoWeAre",
  components: {FeaturesBlock, HeroBlock}
}
</script>

<style lang="scss">
@import "../../assets/styles/pages/who-we-are/who-we-are";
</style>
