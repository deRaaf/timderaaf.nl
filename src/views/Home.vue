<template>
  <div class="home">
    <hero/>
  </div>
</template>

<script>
import hero from '@/components/hero.vue'

export default {
  name: 'Home',
  components: {
    hero,
  }
}
</script>

<style lang="scss">
  .home {
    height: 100%;
    width: 100%;
  }
</style>