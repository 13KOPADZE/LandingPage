<template>
  <div>
    <HeaderComponent />
    <HeroComponent />
    <DestinationCompoent />
    <BoatRegisterComponent />
    <BoatComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import HeroComponent from "./components/HeroComponent";
import DestinationCompoent from "./components/DestinationComponent";
import BoatRegisterComponent from "./components/BoatRegisterComponent";
import BoatComponent from "./components/BoatComponent";
import FooterComponent from "./components/FooterComponent";

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    DestinationCompoent,
    BoatRegisterComponent,
    BoatComponent,
    FooterComponent
  }
};
</script>

<style>
@import url("style/style.css");
</style>
