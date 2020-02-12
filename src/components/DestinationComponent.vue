<template>
  <div>
    <CounterComponent />
    <div class="destination-content">
      <h2>explore our top destinations</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed d kopia
      </p>
    </div>
    <CitiesComponent />
  </div>
</template>
<script>
import CounterComponent from "./CounterComponent";
import CitiesComponent from "./CitiesComponent";
export default {
  name: "HeroComponent",
  components: {
    CitiesComponent,
    CounterComponent
  }
};
</script>
