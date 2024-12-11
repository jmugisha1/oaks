<script setup></script>

<template>
  <nav class="navigation">
    <div class="nav_logo">
      <p>
        oak<br />
        investments<br />
        limited
      </p>
    </div>

    <div class="nav_links">
      <router-link to="/">home</router-link>
      <router-link to="/about">about</router-link>
      <router-link to="/services">services</router-link>
      <router-link to="/services">products</router-link>
      <router-link to="/contact">featured</router-link>
    </div>

    <div class="nav_book">book a call</div>
  </nav>
</template>

<style scoped>
.navigation {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 8px;
  margin-bottom: 1px solid #333;
  color: #333;
  padding: 8px 108px;
  border-bottom: 0.75px solid rgb(0, 0, 0, 0.75);
  width: 100%;
  top: 0;
  left: 0;
  position: fixed;
  z-index: 1000;
  background-color: #f4f4f4;

  .nav_logo {
    p {
      font-size: 16px;
    }
  }

  .nav_links {
    display: flex;
    gap: 32px;
    a {
      font-size: 14px;
      text-transform: uppercase;
      cursor: pointer;
    }
  }
}
</style>
