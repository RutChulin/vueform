<template>
  <v-content>
    <h1>Welcome to the new opportunities</h1>

    <v-divider> </v-divider>

    <div class="text-center">
      <v-chip class="ma-2" color="success" outlined>
        <v-icon left> mdi-server-plus </v-icon>
        Plomeria
      </v-chip>

      <v-chip class="ma-2" color="primary" outlined pill>
        Cocina
        <v-icon right> mdi-account-outline </v-icon>
      </v-chip>

      <v-chip class="ma-2" color="deep-purple accent-4" outlined>
        <v-icon left> mdi-wrench </v-icon>
        Electricidad
      </v-chip>

      <v-chip class="ma-2" close color="indigo darken-3" outlined>
        <v-icon left> mdi-fire </v-icon>
        Limpieza
      </v-chip>
    </div>

    <v-divider></v-divider>

    <v-btn elevation="2">Nuevo Usuario</v-btn>

    <v-hover>
      <template v-slot:default="{ hover }">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <h2 class="text-h6 primary--text">Ocupacion</h2>
            Habilidades, Experiencias, Servicios que brinda
          </v-card-text>

          <v-card-title>
            <v-rating
              :value="4"
              dense
              color="orange"
              background-color="orange"
              hover
              class="mr-2"
            ></v-rating>
            <span class="primary--text text-subtitle-2"> Reviews</span>
          </v-card-title>

          <v-fade-transition>
            <v-overlay v-if="hover" absolute color="#036358">
              <v-btn>See more info</v-btn>
            </v-overlay>
          </v-fade-transition>
        </v-card>
      </template>
    </v-hover>

    <v-hover>
      <template v-slot:default="{ hover }">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <h2 class="text-h6 primary--text">Ocupacion</h2>
            Habilidades, Experiencias, Servicios que brinda
          </v-card-text>

          <v-card-title>
            <v-rating
              :value="4"
              dense
              color="orange"
              background-color="orange"
              hover
              class="mr-2"
            ></v-rating>
            <span class="primary--text text-subtitle-2"> Reviews</span>
          </v-card-title>

          <v-fade-transition>
            <v-overlay v-if="hover" absolute color="#036358">
              <v-btn>See more info</v-btn>
            </v-overlay>
          </v-fade-transition>
        </v-card>
      </template>
    </v-hover>

    <v-hover>
      <template v-slot:default="{ hover }">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <h2 class="text-h6 primary--text">ocupacion</h2>
            Habilidades, Experiencias, Servicios que brinda
          </v-card-text>

          <v-card-title>
            <v-rating
              :value="4"
              dense
              color="orange"
              background-color="orange"
              hover
              class="mr-2"
            ></v-rating>
            <span class="primary--text text-subtitle-2"> Reviews</span>
          </v-card-title>

          <v-fade-transition>
            <v-overlay v-if="hover" absolute color="#036358">
              <v-btn>See more info</v-btn>
            </v-overlay>
          </v-fade-transition>
        </v-card>
      </template>
    </v-hover>

    <v-hover>
      <template v-slot:default="{ hover }">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <h2 class="text-h6 primary--text">ocupacion</h2>
            Habilidades, Experiencias, Servicios que brinda
          </v-card-text>

          <v-card-title>
            <v-rating
              :value="4"
              dense
              color="orange"
              background-color="orange"
              hover
              class="mr-2"
            ></v-rating>
            <span class="primary--text text-subtitle-2">Reviews</span>
          </v-card-title>

          <v-fade-transition>
            <v-overlay v-if="hover" absolute color="#036358">
              <v-btn>See more info</v-btn>
            </v-overlay>
          </v-fade-transition>
        </v-card>
      </template>
    </v-hover>
  </v-content>
</template>
