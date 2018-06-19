<template>
  <div class="container mx-auto">
    <h1 class="text-center text-blue">
      {{ greeting }}! Let's prototype.
    </h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      greeting: 'Hello'
    }
  }
}
</script>

<style lang="scss">
@import '~tailwindcss/dist/tailwind.css';
</style>
