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

    </div>
    <div id="result-field">

    </div>
  </section>
</template>

<style scoped lang="scss">

section {
  :first-child{
    background-color: red;
  }
  :last-child {
    background-color: blue;
  }

  div {
    height: 500px;
    width: 50%;
  }
}


</style>