<template>
  <div class="hero-background">
    <div class="container">
      <div class="hero-contnet">
        <h1>Reserve a boat now!</h1>
        <h2>and set your sails into paradise!</h2>
        <SearchComponent />
      </div>
    </div>
  </div>
</template>
<script>
import SearchComponent from "./SearchComponent";
export default {
  name: "HeroComponent",
  components: {
    SearchComponent
  }
};
</script>
