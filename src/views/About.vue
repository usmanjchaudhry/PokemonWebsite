<template>
  <div class="about">
    <b-container fluid="xl">
    <!-- importing Pokemon component via router (Pokemon.vue) -->
        <Pokemon />
    </b-container>
  </div>
</template>


<script>
import Pokemon from '../components/Pokemon.vue'
export default {
  components: {
    Pokemon
  }
}
</script>


<style scoped>

</style>