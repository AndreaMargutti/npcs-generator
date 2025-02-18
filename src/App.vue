<script>
import AppHeader from './components/header/AppHeader.vue';
import AppMain from './components/main/AppMain.vue';
import AppFooter from './components/footer/AppFooter.vue';

export default {
  data() {
    return {
      
    }
  },

  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}
</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
</template>

<style scoped lang="scss">

div  {
  padding: 5px;
  background-color: #f39b6d;
  color: #4B3F72;
}
</style>