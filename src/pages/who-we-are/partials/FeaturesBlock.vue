<template>
  <div class="features-block">
    <div class="container">
      <div class="block-holder">
        <div class="features-block_text">
          We are <span>technologies </span>
          <div class="features-block_text--item">
            Our team was the first on the market to develop and implement unique multi-channel exchange capabilities
            between CEX and DEX with calculation of all possible details. Our users do not need to manually conduct
            numerous exchanges to buy, sell, trade and invest tokens that have not yet listed on major CEX or are going
            to stay exclusively on DEX platforms, as proven Swapuz algorithms have come to the rescue to save your
            precious time and simplify this process.
          </div>
        </div>
        <div class="features-block-image">
          <img
              srcset="../../../assets/images/png/1features-image1x.png 1x,
               ../../../assets/images/png/1features-image2x.png 2x,
               ../../../assets/images/png/1features-image4x.png 4x"
              src="../../../assets/images/png/1features-image2x.png" alt="features-image">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FeaturesBlock"
}
</script>

<style lang="scss">@import "../../../assets/styles/pages/who-we-are/partials/features-block.scss";

</style>
