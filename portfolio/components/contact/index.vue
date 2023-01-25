<template>
  <div>
    <v-col class="text-center">
      <h1 style="color: #424242; padding: 8px">Contact Me</h1>
      <p style="color: grey; padding: 8px">Get in touch</p>
    </v-col>

    <v-col cols="12" sm="12" md="12" class="text-center">
      <v-card class="mx-auto" max-width="800" elevation="0">
        <v-col>
          <v-form ref="form" v-model="valid" lazy-validation>
            <v-text-field
              v-model="name"
              :rules="nameRules"
              label="Name"
              required
              outlined
            ></v-text-field>

            <v-text-field
              v-model="email"
              :rules="emailRules"
              label="E-mail"
              required
              outlined
            ></v-text-field>

            <v-textarea
              v-model="detail"
              label="Detail"
              outlined
              :rules="detailRules"
              row-height="25"
              required
            ></v-textarea>

            <v-btn
              color="grey darken-3"
              
              dark
              @click="validate"
            >
              Validate
              <v-icon right dark> mdi-send-outline </v-icon>
            </v-btn>
          </v-form>
        </v-col>
      </v-card>
      <v-col cols="12" sm="12" md="12" class="pt-12">
            <v-btn
              class="mx-2"
              fab
              dark
              small
              color="grey"
              icon
              href="https://www.instagram.com/18_tttt/"
              target="_blank"
            >
              <v-icon dark> mdi-instagram </v-icon> </v-btn
            ><v-btn
              class="mx-2"
              fab
              dark
              small
              color="grey"
              icon
              href="https://www.linkedin.com/in/nontawat-wichapha-237219209/"
              target="_blank"
            >
              <v-icon dark> mdi-linkedin </v-icon> </v-btn
            ><v-btn
              class="mx-2"
              fab
              dark
              small
              color="grey"
              icon
              href="https://github.com/nontawat18"
              target="_blank"
            >
              <v-icon dark> mdi-github </v-icon>
            </v-btn>
          </v-col>
          <p style="color: grey; padding: 8px">+66 92 443 4736 <br/> nontawatwichapha1998@gmail.com</p>
    </v-col>
  </div>
</template>
<script>
export default {
  data: () => ({
    valid: true,
    name: "",
    nameRules: [(v) => !!v || "Name is required"],
    detailRules: [(v) => !!v || "Detail is required"],
    detail: "",
    email: "",
    emailRules: [
      (v) => !!v || "E-mail is required",
      (v) => /.+@.+\..+/.test(v) || "E-mail must be valid",
    ],
    select: null,
    items: ["Item 1", "Item 2", "Item 3", "Item 4"],
    checkbox: false,
  }),

  methods: {
    validate() {
      this.$refs.form.validate();
    },
    reset() {
      this.$refs.form.reset();
    },
    resetValidation() {
      this.$refs.form.resetValidation();
    },
  },
};
</script>
