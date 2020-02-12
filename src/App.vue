<template>
  <div>
    <HeaderComponent />
    <HeroComponent />
    <CounterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import HeroComponent from "./components/HeroComponent";
import CounterComponent from "./components/CounterComponent";

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    CounterComponent
  }
};
</script>

<style>
@import url("style/style.css");
</style>
