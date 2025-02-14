<script>
export default {
  data() {
    return {
      // nome componente
      name: 'AppHeader',
      // dati lista
      hamburgerMenu: [
        'My Npcs',
        'Feedback'
      ],
    }
  },
  
}
</script>

<template>
    <section class="d-flex justify-content-between">
      <div>
        <h1>NPCs - Generator</h1>
      </div>
      <!-- sezione lista menu -->
      <div>
        <ul class="d-flex">
          <li v-for="item in hamburgerMenu">{{ item }}</li>
        </ul>
      </div>
    </section>
</template>

<style scoped lang="scss">
  // titolo
  h1 {
    font-family: 'Grenze Gotisch', sans-serif;
    font-weight: 800;
    font-size: 2.5rem;
  }

  // lista
  ul {
    list-style-type: none;
    font-family: 'Grenze Gotisch', sans-serif;
    font-size: 2.3rem;
    font-weight: 600;
    gap: 15px;
  }
</style>