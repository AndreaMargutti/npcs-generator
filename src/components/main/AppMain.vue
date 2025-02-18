<script>
export default {
  data() {
    return {
      name: 'AppMain',
    }
  }
}
</script>

<template>
  <section class="d-flex">
    <!-- sezione possibili input -->
    <div id="input-field">
        <label for="name">Nome:</label>
        <input type="text" id="name">
        
        <label for="type">Classe:</label>
        <select name="type" id="type">
          <option selected>Casuale</option>
          <option value="guerriero">Guerriero</option>
          <option value="stregone">Stregone</option>
          <option value="warlock">Warlock</option>
          <option value="monaco">Monaco</option>
        </select>
        
        <label for="race">Razza:</label>
        <select name="race" id="race">
          <option selected>Casuale</option>
          <option value="umano">Umano</option>
          <option value="elfo">Elfo</option>
          <option value="mezz-orco">Mezz'Orco</option>
          <option value="tiefling">Tiefling</option>
        </select>
        
        <button>CREA NPC</button>
    </div>
    <!-- sezione display result -->
    <div id="result-field">
      <h1>Qui ci sarà la scheda dell'NPC</h1>
    </div>
  </section>
</template>

<style scoped lang="scss">

section {
  :first-child{
    border: 5px solid red;
  }
  :last-child {
    border: 5px solid blue;
  }

  div {
    height: 500px;
    width: 50%;
  }
}


</style>