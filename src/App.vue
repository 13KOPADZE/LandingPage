<template>
  <div>
    <HeaderComponent />
    <HeroComponent />
    <DestinationCompoent />
    <BoatRegisterComponent />
    <BoatComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import HeroComponent from "./components/HeroComponent";
import DestinationCompoent from "./components/DestinationComponent";
import BoatRegisterComponent from "./components/BoatRegisterComponent";
import BoatComponent from "./components/BoatComponent";

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    DestinationCompoent,
    BoatRegisterComponent,
    BoatComponent
  }
};
</script>

<style>
@import url("style/style.css");
</style>
