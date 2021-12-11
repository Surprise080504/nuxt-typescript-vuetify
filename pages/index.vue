<template>
  <v-app>
    <v-app-bar app color="dark" shaped elevation="4">
      <v-btn icon color="info" outlined nuxt to="/">
        <v-icon x-large color="info">mdi-simple-icons</v-icon>
      </v-btn>
      <!-- <v-toolbar-title style="margin-top: 16px; margin-left: -6px"
        >chedule</v-toolbar-title
      > -->
      <v-spacer></v-spacer>
      <div>
        <v-btn color="info" outlined nuxt to="/auth/login">
          <v-icon>mdi-login</v-icon>
          Log In
        </v-btn>
      </div>
      <div>
        <v-btn color="primary" nuxt to="/auth/signup">
          <v-icon>mdi-account</v-icon>
          Sign up
        </v-btn>
      </div>
    </v-app-bar>
    <v-main>
      <v-container>
        <v-col>
          <v-alert elevation="7" dismissible color="purple" type="info" shaped
            >I hope you will introduce higher clients to me. I wiil trust you.
          </v-alert>
        </v-col>
      </v-container>
    </v-main>
  </v-app>
</template>
<script>
// import Header from "./components/layout/Header.vue";

// export default {
//   components: {
//     Header,
//   },
// };
</script>