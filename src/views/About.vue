<template>
  <div id="about">
    <h1 id="header">Wanna see some whales? Press -></h1>
    <VueSlickCarousel :arrows="true" :dots="true">
      <!-- Blue whale -->
      <div>
        <img src=https://www.nwf.org/-/media/NEW-WEBSITE/Shared-Folder/Wildlife/Mammals/mammal_blue-whale_eco2drew-GettyImages_600x300.ashx>
        <h2>Blue Whale</h2>
        <p>The blue whale has the largest heart of any living creature.</p>
      </div>
      <!-- Southern Right Whale -->
      <div>
        <img src=https://polarjournal.ch/wp-content/uploads/2020/05/Southern-right-whale_Shutterstock_wildestanimal.jpg>
        <h2>Southern Right Whale</h2>
        <p>Those distinctive white patches? Colonies of parasites. Yuck!</p>
      </div>
      <!-- Narwhals-->
      <div>
        <img src=https://a-z-animals.com/media/narwhal-6.jpg>
        <h2>Narwhal</h2>
        <p> Narwhals have the longest tooth of any animal- ever!</p>
      </div>
      <div>
        <img src=https://storage.googleapis.com/oceanwide_web/media-dynamic/cache/widen_1600/media/default/0001/28/8ab74d02b8cf1ec1459365288f6bb1175ee41bd7.jpeg>
        <h2>Sperm Whale</h2>
        <p>Sperm whales are able to hold their breath for over an hour and half, at depths of about 3,000m.</p>
      </div>
      <div>
        <h1>Bonus: Where's the killer whale?</h1>
        <img src=https://res.cloudinary.com/dk-find-out/image/upload/q_70,c_pad,w_1200,h_630,f_auto/Question_mark_icon_fofmid.jpg>
        <h3>They're not whales, silly! Orca's are dolphins, and the largest dolphin species in the ocean.</h3>
      </div>

    </VueSlickCarousel>
  </div>
</template>

<style>
#header {
  color: white;
  background-color: darkcyan;
}
img {
  margin: 0 auto;
  max-width: 600px;
}
</style>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "MyComponent",
  components: { VueSlickCarousel },
};
</script>