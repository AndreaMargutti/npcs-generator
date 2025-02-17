<script>
import AppHeader from './components/header/AppHeader.vue';
import AppMain from './components/main/AppMain.vue';

export default {
  data() {
    return {
      
    }
  },

  components: {
    AppHeader,
    AppMain,
  }
}
</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain />
  </div>
</template>

<style scoped lang="scss">

div  {
  background-color: #f39b6d;
  color: #4B3F72;
}
</style>