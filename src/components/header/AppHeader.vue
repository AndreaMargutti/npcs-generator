<script>
export default {
  data() {
    return {
      name: 'AppHeader',
      hamburgerMenu: [
        'My Npcs',
        'Feedback'
      ],
    }
  },
  
}
</script>

<template>
    <section>
      <div>
        <h1>NPCs - Generator</h1>
      </div>
      <!-- sezione lista menu -->
      <div>
        <ul>
          <li v-for="item in hamburgerMenu">{{ item }}</li>
        </ul>
      </div>
    </section>
</template>

<style scoped lang="scss">
  h1 {
    font-family: 'Grenze Gotisch', sans-serif;
    font-weight: 800;
    font-size: 2.5rem;
    margin: 0;
  }
</style>