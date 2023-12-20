<script>
export default {
  name: 'AppHero'
}
</script>

<template>
  <section>
    <div class="jumbo">
      <h1>Vite + Vue</h1>
      <img src="../assets/jumbo.webp" alt="">
    </div>
  </section>
</template>

<style scoped>
.jumbo {
  position: relative;
}

h1 {
  position: absolute;
  top: 1rem;
  left: 50%;
  transform: translateX(-50%);
}

img {
  width: 100%;
}
</style>