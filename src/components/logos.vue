<template>
  <div class="logos">
    <div class="logos-wrapper">
      <h2 class="title-header">Find Best Logo</h2>
      <div class="item-logos">
        <img class="logo" alt="hotel logo" src="../assets/hotel.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="pin logo" src="../assets/pin.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="receptionist logo" src="../assets/receptionist.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="hotel logo" src="../assets/hotel.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="pin logo" src="../assets/pin.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="receptionist logo" src="../assets/receptionist.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="hotel logo" src="../assets/hotel.png" />
      </div>
      <div class="item-logos">
        <img class="logo" alt="pin logo" src="../assets/pin.png" />
      </div>
    </div>
  </div>
</template>

//Logical seperti API
<script>
export default {
  name: "logos"
};
</script>


// Costum Style css
<style scoped>
.title-header {
  text-align: left;
  margin-bottom: 80px;
}
.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}
.item-logos {
  float: left;
  margin-right: 80px;
  margin-bottom: 80px;
  width: 150px;
  height: 150px;
}
.item-logos .logo {
  width: 150px;
  height: 150px;
}
</style>