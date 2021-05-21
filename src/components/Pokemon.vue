<template>
  <div class="container">
    <!-- a way to structure the List and Detail -->
    <h1 class="animate__animated animate__bounce">Pokedex</h1>
       <PokemonList 
      :imageUrl="imageUrl" 
      :apiUrl="apiUrl"
      @setPokemonUrl="setPokemonUrl" />
    <PokemonDetail 
      v-if="showDetail"
      :pokemonUrl="pokemonUrl"
      :imageUrl="imageUrl"
      @closeDetail="closeDetail" />
  </div>
</template>

<!-- import data from PokemonList and PokemonDetail we are getting info from API like name and details, images coming from Sprites via githubusercontent (the imageUrl) -->
<script>

  import PokemonList from './PokemonList.vue';
  import PokemonDetail from './PokemonDetail.vue';

  export default {
    data: () => {
      return {
        imageUrl: 'https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/',
        apiUrl: 'https://pokeapi.co/api/v2/pokemon/',
        pokemonUrl: '',
        showDetail: false
      }
    },
    components: {
    
      PokemonList,
       PokemonDetail
    },
    methods: {
      setPokemonUrl(url) {
        this.pokemonUrl = url;
        this.showDetail = true;
      },
      closeDetail() {
        this.pokemonUrl = '';
        this.showDetail = false;
      }
    }
  }
</script>
<!-- some styles for Pokemon container using flex (its the background thats blue) -->
<style>
  @import url('https://fonts.googleapis.com/css?family=Acme');

    
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 10px;
    width: calc(100% - 20px);
    min-height: calc(100vh - 20px);
    background: radial-gradient(#156F99, #0A2E50);

    font-family: 'Acme', arial;
    font-size: 1rem;
    font-weight: normal;
   
  }

  h1 { color: white;}


</style>
