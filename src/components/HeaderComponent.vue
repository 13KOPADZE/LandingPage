<template>
  <header class="header">
    <div class="container">
      <div class="header-inner">
        <img class="logo" src="../image/logo.png" />
        <div class="mobile-nav-toggler" @click="toggleNav()">
          <div class="bar1"></div>
          <div class="bar2"></div>
          <div class="bar3"></div>
        </div>
        <nav class="nav-bar">
          <ul>
            <li>top destinations</li>
            <li>add your boat</li>
            <li>
              <button>sign up</button>
            </li>
          </ul>
        </nav>
        <nav
          class="mobile-nav"
          v-if="isActive"
          v-bind:class="{ active: isActive }"
        >
          <ul>
            <li>top destinations</li>
            <li>add your boat</li>
            <li>
              <button>sign up</button>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  data() {
    return {
      isActive: false
    };
  },
  methods: {
    toggleNav() {
      if (this.isActive) {
        this.isActive = false;
      } else {
        this.isActive = true;
      }
    }
  }
};
</script>
<style>
.active {
  display: block !important;
}
</style>
