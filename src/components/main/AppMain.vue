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
    <div id="input-field">
        <button>GENERA</button>
    </div>
    <!-- sezione display result -->
    <div id="result-field">

    </div>
  </section>
</template>

<style scoped lang="scss">

section {

  #input-field {
    border: 5px solid red;
  }

  #result-field {
    border: 5px solid blue;
  }

  div {
    height: 500px;
    width: 50%;
  }
}


</style>