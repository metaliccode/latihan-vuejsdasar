<template>
  <div class="Profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="media text-left">
            <img alt="foto yova" src="../assets/yova.png" class="user-pic mr-3" />
            <div class="media-body">
              <h5>{{ firstName }} {{lastName}}</h5>
              <p>{{Biodata}}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "Profile",
  data: function() {
    return {
      firstName: "Yova ",
      lastName: "Oktaviari",
      Biodata:
        "Mahasiswa Hukum Sayariah yang berasal dari kota Tasikmalaya seorang bocil yang tangkas suka bermain"
    };
  },
  components: {
    //HelloWorld
  }
};
</script>

<style scoped>
.user-pic {
  width: 80px;
  height: 80px;
  border-radius: 200%;
}
</style>
