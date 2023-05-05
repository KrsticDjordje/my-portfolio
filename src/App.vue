<template>
  <v-app>
    <v-app-bar app color="white" dark>
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="colorlib-navbar-brand">
              <a class="colorlib-logo" href="index.html"
                ><span>No</span><span>ah</span></a
              >
            </div>
            <a href="#" class="js-colorlib-nav-toggle colorlib-nav-toggle"
              ><i></i
            ></a>
          </div>
        </div>
      </div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
<style>
@import "@/assets/css/style.css";
</style>
