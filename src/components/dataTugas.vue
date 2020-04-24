<template>
  <div class="form-check">
    <input class="form-check-input" type="checkbox" value id="defaultCheck1" />
    <label
      class="form-check-label"
      for="defaultCheck1"
      v-bind:class="{'item-completed':tugasSaya.idDone}"
    >{{tugasSaya.nama}}</label>
  </div>
</template>

<script>
export default {
  name: "dataTugas",
  props: ["tugasSaya"]
};
</script>

<style scoped>
</style>