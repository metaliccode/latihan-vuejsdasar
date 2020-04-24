<template>
  <div class="about">
    <div class="container">
      <div class="row header">
        <div class="col-lg-12 mb-2 p-2">
          <h2>What I do to day ?</h2>
        </div>
      </div>
      <div class="row content mt-5">
        <div class="col-lg-12">
          <div class="pekerjaan-rumah">
            <div class="row">
              <div
                v-for="tugasSaya in tugas"
                v-bind:key="tugasSaya.id"
                class="tugas text-left mb-2 col-12"
              >
                <dataTugas v-bind:tugasSaya="tugasSaya" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import dataTugas from "../components/dataTugas.vue";

export default {
  name: "about",
  data: function() {
    return {
      tugas: [
        {
          id: 1,
          nama: "Membersihkan toilet",
          idDone: false
        },
        {
          id: 2,
          nama: "Menyapu lantai",
          idDone: true
        },
        {
          id: 3,
          nama: "Olahraga",
          idDone: false
        }
      ]
    };
  },
  components: {
    dataTugas
  }
};
</script>

<style>
.header {
  background: powderblue;
}
.header h2 {
  margin: 0;
}
.item-completed {
  color: greenyellow;
}
</style>