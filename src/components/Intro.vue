<template>
  <section>
    <div class="hero_text">
      <h1>A Simple Bookmark Manager</h1>
      <p>
        A clean and simple interface to organize your favourite websites. Open a
        new browser tab and see your sites load instantly. Try it for free.
      </p>
      <div class="hero-buttons">
        <myButton text='Get it on Chrome' color='blue' />
        <myButton text="Get it on Firefox" color="gray" />
      </div>
    </div>

    <div class="hero_image">
      <img src="../assets/illustration-hero.svg" alt="" />
    </div>
  </section>
</template>

<style scoped>
section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 100px;
  min-width: 100%;
}
.hero_text {
  max-width: 50%;
  display: flex;
  flex-direction: column;
  gap: 30px;
}

h1 {
  font-size: 3rem;
  line-height: 2.75rem;
  color: black;
  margin-right: 50px;
}
p {
  margin-right: 230px;
  line-height: 2rem;
}
.hero_image {
  display: flex;
  align-items: flex-end;
}

.hero_image img {
  justify-self: flex-end;
}
.hero-buttons{
display: flex;
gap: 20px;
}
</style>
<script setup>
import myButton from "./myButton.vue";
</script>
