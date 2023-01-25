<template>
  <div class="who-we-are">
    <hero-block/>
  </div>
</template>

<script>
import HeroBlock from "@/pages/who-we-are/partials/HeroBlock.vue";

export default {
  name: "WhoWeAre",
  components: {HeroBlock}
}
</script>

<style lang="scss">
@import "../../assets/styles/pages/who-we-are/who-we-are";
</style>
