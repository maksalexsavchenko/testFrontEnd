<template>
  <div class="hero-block">
    <img src="../../../assets/images/svg/hero-bg.svg" alt="hero-bg" class="hero-block_bg">
    <div class="container">
      <div class="block-holder">
        <div class="hero-block_text">
          Who <span>we</span> are?
          <div class="hero-block_text--item">
            Swapuz is a fast, unlimited and fully transparent cryptocurrency exchange created in 2019 by a team
            of
            professionals that aims to provide its users with a unique cryptocurrency exchange experience by
            creating an
            intuitive, simple and user-friendly interface for institutional traders and beginners. Don't bother
            with
            CEX
            and DEX - use Swapuz.
          </div>
          <div class="hero-block_text--next">
            Our mission
            <div class="hero-block_text--next-item">
              The user always comes first for us, that's why the main mission of Swapuz is to be a reliable provider
              of
              exchange products and other services for users of the cryptocurrency ecosystem.
            </div>
          </div>
        </div>
        <div class="hero-block-image">
          <img
              srcset="../../../assets/images/png/hero-image1x.png 1x,
               ../../../assets/images/png/hero-image2x.png 2x,
               ../../../assets/images/png/hero-image4x.png 4x"
              src="../../../assets/images/png/hero-image2x.png" alt="hero-image">
        </div>
      </div>
    </div>
  </div>
  <div class="cards">
    <div class="container">
      <div class="cards-main">
        <div class="card">

          <div class="card-title">
            1000000+ <br>transactions
            <div class="card-title-desc">
              Swapuz provides the best <br>exchange rate and transparent <br>fee structure with no hidden fee.
            </div>
          </div>
          <div class="card-image">
            <div class="card-img">
              <img
                  srcset="../../../assets/images/png/1vector.png
               ../../../assets/images/png/1vector2x.png 2x,
               ../../../assets/images/png/1vector4x.png 4x"
                  src="../../../assets/images/png/1vector2x.png" alt="vector1">
            </div>
          </div>
        </div>
        <!--      !!! card 2 !!!-->
        <div class="card2">

          <div class="card-title">
            11387 users <br>trust us
            <div class="card-title-desc">
              Users stay with us as Swapuz<br> strives to meet and support<br> everyone's unique needs
            </div>
          </div>
          <div class="card-image">
            <div class="card-img">
              <img
                  srcset="../../../assets/images/png/2vector.png
               ../../../assets/images/png/2vector2x.png 2x,
               ../../../assets/images/png/2vector4x.png 4x"
                  src="../../../assets/images/png/2vector.png" alt="vector2">
            </div>
          </div>
        </div>
        <!--      !!!card3!!!-->
        <div class="card3">

          <div class="card-title">
            48 patrners <br>growth with us
            <div class="card-title-desc">
              Swapuz offers comprehensive<br> solutions and set of tools to meet<br> the needs of partners fee.
            </div>
          </div>
          <div class="card-image">
            <div class="card-img">
              <img
                  srcset="../../../assets/images/png/3vector.png
               ../../../assets/images/png/3vector2x.png 2x,
               ../../../assets/images/png/3vector4x.png 4x"
                  src="../../../assets/images/png/3vector2x.png" alt="vector3">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "HeroBlock"
}
</script>

<style lang="scss">@import "../../../assets/styles/pages/who-we-are/partials/hero-block";
</style>
