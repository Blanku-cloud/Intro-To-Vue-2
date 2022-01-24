<template>
  <div class="home">
    <h1>{{ now }}</h1>
    <Button v-for="pokemonlol in pokemons" :key="pokemonlol">{{
      pokemonlol
    }}</Button>
  </div>
</template>

<script>
// @ is an alias to /src
import Button from "../components/Button1.vue";
export default {
  name: "Home",
  components: {
    Button,
  },
  data() {
    return {
      pokemons: ["Pikachu", "Eevee", "Garchomp", "Gardevoir"],
    };
  },
  computed: {
    now: function () {
      const time = new Date();
      return `${time.getHours()}:${time.getMinutes()}`;
    },
  },
  methods: {},
};
</script>
<style></style>
