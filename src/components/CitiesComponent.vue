<template>
  <div>
    <div class="grid-content">
      <div class="grid">
        <div class="grid-element">
          <div class="boat-number">
            <IconComponent name="boat_icon" />
            <p>730</p>
          </div>
          <img src="../image/destination-1.png" />
          <div class="cities-info">
            <h3>Figueira da Foz</h3>
            <p>Portugal</p>
          </div>
        </div>
        <div class="grid-element">
          <div class="boat-number">
            <IconComponent name="boat_icon" />
            <p>621</p>
          </div>
          <img src="../image/destination-2.png" />
          <div class="cities-info">
            <h3>Ibiza</h3>
            <p>Spain</p>
          </div>
        </div>
        <div class="grid-element">
          <div class="boat-number">
            <IconComponent name="boat_icon" />
            <p>543</p>
          </div>
          <img src="../image/destination-3.png" />
          <div class="cities-info">
            <h3>Palma de Mallorca</h3>
            <p>Spain</p>
          </div>
        </div>
        <div class="grid-element">
          <div class="boat-number">
            <IconComponent name="boat_icon" />
            <p>495</p>
          </div>
          <img src="../image/destination-4.png" />
          <div class="cities-info">
            <h3>Portofino</h3>
            <p>Italy</p>
          </div>
        </div>
        <div class="grid-element">
          <div class="boat-number">
            <IconComponent name="boat_icon" />
            <p>402</p>
          </div>
          <img src="../image/destination-5.png" />
          <div class="cities-info">
            <h3>Port Hercules</h3>
            <p>Monaco</p>
          </div>
        </div>
      </div>
      <button>explore more destinations</button>
    </div>
  </div>
</template>

<script>
import IconComponent from "./IconComponent";
export default {
  name: "CitiesComponent",
  components: {
    IconComponent
  }
};
</script>
