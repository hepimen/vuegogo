<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="d-flex">
            <div class="flex-shrink-0">
              <img
                src="../assets/logo-profile.png"
                alt="myLogo"
                class="user-pic"
              />
            </div>
            <div class="flex-grow-1 ms-3 text-left">
              <h4>{{ firstName }} {{ lastName }}</h4>
              <p>{{ bio }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "profile",
  data: function () {
    return {
      firstName: "Jakson",
      lastName: "Tiago",
      bio: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.",
    };
  },
  components: {},
};
</script>
<style scoped>
.user-pic {
  margin-top: -50px;
  height: 200px;
  width: 200px;
}
.text-left {
  text-align: left;
}
</style>
