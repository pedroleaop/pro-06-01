<template>
  <div class="teste-if">
      <h2 v-if="podeVer">Agora você consegue ver!</h2>
      <h2 v-else> Agora não...</h2>
  </div>
</template>

<script>
export default {
    name: 'testeif',
    data() {
        return {
            podeVer:true
        }
    }

}
</script>

<style scoped>

</style>