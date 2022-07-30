<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Bienvenidos</h1>
    <button @click="goToDiario" class="btn btn-success">Diario</button>
    <button @click="goToDiario" class="btn btn-danger">Diario2</button>
    <button @click="goToDiario" class="btn btn-info">Diario3</button>
  </div>
</template>
<script>
  export default {
    methods: {
      goToDiario() {
        this.$router.push({name: 'no-entrada'})
      }
    }
  }
</script>
