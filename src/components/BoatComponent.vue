<template>
  <div>
    <section class="boat-content container">
      <div class="boat-headings">
        <h2>featured boats</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
          eiusmod
        </p>
      </div>
      <div class="boat-grid">
        <div class="boat-grid-element">
          <div class="boat-price">
            <p>€580 / day</p>
          </div>
          <img src="../image/boat-1.png" />
          <div class="boat-info">
            <h3>Delphia 47</h3>
            <div class="d-flex">
              <div class="d-flex">
                <IconComponent name="place" />
                Gdańsk, Poland
              </div>
              <div class="d-flex">
                <IconComponent name="berth" />
                8 Berths
              </div>
            </div>
          </div>
        </div>
        <div class="boat-grid-element">
          <div class="boat-price">
            <p>€950 / day</p>
          </div>
          <img src="../image/boat-2.png" />
          <div class="boat-info">
            <h3>Sense 55</h3>
            <div class="d-flex">
              <div class="d-flex">
                <IconComponent name="place" />
                Portofino, Italy
              </div>
              <div class="d-flex">
                <IconComponent name="berth" />
                12 Berths
              </div>
            </div>
          </div>
        </div>
        <div class="boat-grid-element">
          <div>
            <div class="boat-price">
              <p>€820 / day</p>
            </div>
            <img src="../image/boat-3.png" />
            <div class="boat-info">
              <h3>Crusier 51</h3>
              <div class="d-flex">
                <div class="d-flex">
                  <IconComponent name="place" />
                  Palma de Mallorca, Spain
                </div>
                <div class="d-flex">
                  <IconComponent name="berth" />
                  10 Berths
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="boat-grid-element ">
          <div>
            <div class="boat-price">
              <p>€400 / day</p>
            </div>
            <img src="../image/boat-4.png" />
            <div class="boat-info">
              <h3>Cruiser 14S</h3>
              <div class="d-flex">
                <div class="d-flex">
                  <IconComponent name="place" />
                  Lisbon, Portugal
                </div>
                <div class="d-flex">
                  <IconComponent name="berth" />
                  8 Berths
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <button>load more boats</button>
    </section>
  </div>
</template>

<script>
import IconComponent from "./IconComponent";
export default {
  components: {
    IconComponent
  }
};
</script>
