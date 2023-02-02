<template>
  <div class="who-we-are">
    <hero-block/>
    <features-block/>
    <partners-block/>
    <info-block/>
  </div>
</template>

<script>
import HeroBlock from "@/pages/who-we-are/partials/HeroBlock.vue";
import FeaturesBlock from "@/pages/who-we-are/partials/FeaturesBlock";
import PartnersBlock from "@/pages/who-we-are/partials/PartnersBlock";
import InfoBlock from "@/pages/who-we-are/partials/InfoBlock";

export default {
  name: "WhoWeAre",
  components: {InfoBlock, PartnersBlock, FeaturesBlock, HeroBlock}
}
</script>

<style lang="scss">
@import "../../assets/styles/pages/who-we-are/who-we-are";
</style>
