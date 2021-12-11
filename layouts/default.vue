<template>
  <v-app dark>
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
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {}
</script>
