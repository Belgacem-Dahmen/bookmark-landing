<template>
  <div class="navbar">
    <div>
      <img src="../assets/logo-bookmark.svg" alt="" />
    </div>
    <div class="links">
      <p class="link">Features</p>
      <p class="link">Pricing</p>
      <p class="link">Contact</p>
      <myButton text="LOGIN" color="red" />
    </div>
  </div>
</template>

<style>
.navbar {
  display: flex;
  align-items: center;
  padding: 20px 0;
  justify-content: space-between;
}

.links {
  display: flex;
  align-items: center;
  gap: 50px;
  padding-right: 50px;
}

.link {
  cursor: pointer;
  text-transform: uppercase;
  letter-spacing: 1.125px;
  font-weight:500;
}
.link:hover {
  color: var(--primary-soft-red);
}
</style>

<script setup>
import myButton from "./myButton.vue";
</script>
