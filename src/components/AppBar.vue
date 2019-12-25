<template>
    <div>
        <v-app-bar
      app
      color="gray"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="underpants logo"
          class="shrink mr-2"
          contain
          :src="require('/home/bbto/Documents/crud-ch/src/assets/jeje2.png')"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="chon admin"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          :src="require('/home/bbto/Documents/crud-ch/src/assets/chon.jpg')"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
      text
      >
      <span class="mr-2">Registrarse</span>

      </v-btn>
      <v-btn
        text
      >
        <span class="mr-2">Iniciar sesion</span>
        <v-icon>fas fa-sign-in-alt</v-icon>
      </v-btn>
    </v-app-bar>
    </div>
</template>