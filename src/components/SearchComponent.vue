<template>
  <div>
    <div class="relative">
      <input
        class="search-input"
        placeholder="What is your destination, sailor?"
        type="text"
      />
      <span class="search-info">
        <IconComponent name="boat_icon" />
        find a boat</span
      >
    </div>
  </div>
</template>

<script>
import IconComponent from "./IconComponent";
export default {
  name: "SearchComponent",
  components: {
    IconComponent
  }
};
</script>
