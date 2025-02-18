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
        
    </div>
    <!-- sezione display result -->
    <div id="result-field">

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