<template>
  <div>
    <v-col class="text-center">
      <h1 style="color: #424242; padding: 8px">Skills</h1>
      <p style="color: grey; padding: 8px">My Tecnical level</p>
    </v-col>
    <v-row class="pt-4 pb-4">
      <v-col cols="12" sm="6" md="6" class="text-center ">
        <v-card class="mx-auto " max-width="600">
          <h2 style="color: #424242; padding: 8px">Frontend Developer</h2>

          <v-card-text>
            <v-row align="center" class="mx-0">
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">HTML</h3>

                <v-rating
                  :value="4"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">CSS</h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="16"
                ></v-rating>
              </v-col>
            </v-row>
            <v-divider class="ma-4"></v-divider>
            <v-row align="center" class="mx-0">
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Javascript</h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Git</h3>

                <v-rating
                  :value="4"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="16"
                ></v-rating>
              </v-col>
            </v-row>
            <v-divider class="ma-4"></v-divider>
            <v-row align="center" class="mx-0">
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Vuetify </h3>

                <v-rating
                  :value="4"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Nuxt.js</h3>

                <v-rating
                  :value="4"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="16"
                ></v-rating>
              </v-col>
            </v-row>
            <v-divider class="ma-4"></v-divider>
            <v-row align="center" class="mx-0">
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">React.js </h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Vite.js</h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="16"
                ></v-rating>
              </v-col>
            </v-row>
          </v-card-text>

        </v-card>
      </v-col>
      <v-col cols="12" sm="6" md="6" class="text-center">
        <v-card class="mx-auto " max-width="600">
          <h2 style="color: #424242; padding: 8px">Backend Developer</h2>

          <v-card-text>
            <v-row align="center" class="mx-0">
              <v-col cols="6" sm="6" md="6"  class="text-center">
                <h3 style="color: #424242; padding: 8px">Python</h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">SQL</h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
            </v-row>
            <v-divider class="ma-4"></v-divider>
            <v-row align="center" class="mx-0">
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Odoo </h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="14"
                ></v-rating>
              </v-col>
              <v-col cols="6" sm="6" md="6">
                <h3 style="color: #424242; padding: 8px">Django</h3>

                <v-rating
                  :value="3"
                  color="grey darken-3"
                  dense
                  half-increments
                  readonly
                  size="16"
                ></v-rating>
              </v-col>
            </v-row>
          </v-card-text>

          <v-divider class="mx-4"></v-divider>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>
<script>
export default {};
</script>
