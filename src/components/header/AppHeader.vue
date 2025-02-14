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
    <section class="d-flex justify-content-between align-items-center">
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
    font-family: var(--main-font-family);
    font-weight: 800;
    font-size: var(--main-title-size)
  }

  // lista
  ul {
    list-style-type: none;
    font-family: var(--main-font-family);
    font-size: 2rem;
    font-weight: 600;
    gap: 15px;
  }
</style>