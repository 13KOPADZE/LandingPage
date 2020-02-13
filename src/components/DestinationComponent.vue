<template>
  <div class="container">
    <CounterComponent />
    <div class="destination-content">
      <h2>explore our top destinations</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna
      </p>
    </div>
    <CitiesComponent />
  </div>
</template>
<script>
import CounterComponent from "./CounterComponent";
import CitiesComponent from "./CitiesComponent";

export default {
  name: "DestinationCompoent",
  components: {
    CounterComponent,
    CitiesComponent
  }
};
</script>
