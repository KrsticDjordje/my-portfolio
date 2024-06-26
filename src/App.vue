<template>
  <v-app>
    <v-toolbar app color="white" dark>
      <v-container>
        <v-row align="center">
          <v-col cols="auto">
            <div class="colorlib-navbar-brand">
              <a class="colorlib-logo" href="">
                <img :src="require('@/assets/myLogo.png')" width="60" />
              </a>
            </div>
          </v-col>

          <v-spacer></v-spacer>

          <span class="mdi mdi-menu-open"></span>
        </v-row>
      </v-container>
    </v-toolbar>

    <v-main>
      <router-view />
    </v-main>

    <footer>
      <div id="footer">
        <div class="container">
          <div class="row">
            <div class="col-md-12 text-center">
              <p>© 2024 Djordje Krstić</p>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      drawer: false,
    };
  },
};
</script>
<style>
@import "@/assets/css/style.css";

header {
  height: 120px !important;
  width: 100%;
  box-shadow: none !important;
}
</style>
