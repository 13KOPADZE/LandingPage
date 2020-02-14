<template>
  <footer>
    <div class="footer-border"></div>
    <div class="footer-content container">
      <div class="footer-text">
        <h3>top locations</h3>
        <p>
          Lorem ipsum dolor Sit amet consectetur Adipisicing elit Eiusmo tempor
        </p>
      </div>
      <div class="footer-text">
        <h3>featured boats</h3>
        <p>
          Lorem ipsum dolor Sit amet consectetur Adipisicing elit Eiusmo tempor
        </p>
      </div>
      <div class="footer-subscribe">
        <h3>subscribe to our newsletter</h3>
        <div class="footer-input">
          <input
            class="footer-search-input"
            placeholder="Your email adress"
            type="text"
          />
          <span class="footer-search-info">subscribe</span>
        </div>
        <div class="d-flex">
          <IconComponent class="icon-component" name="facebook" />
          <IconComponent class="icon-component" name="twitter" />
          <IconComponent class="icon-component" name="google" />
        </div>
      </div>
      <div class="footer-text">
        <h3>contact us</h3>
        <p>
          Lorem ipsum dolor Sit amet consectetur Adipisicing elit Eiusmo tempor
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
import IconComponent from "./IconComponent";
export default {
  components: {
    IconComponent
  }
};
</script>
