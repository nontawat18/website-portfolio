<template>
  <div>
    <v-col class="text-center">
      <h1 style="color: #424242; padding: 8px">Portfolio</h1>
      <p style="color: grey; padding: 8px">My Tecnical level</p>
    </v-col>
    <v-tabs
      v-model="tab"
      background-color="wihte"
      centered
      icons-and-text
      color="grey darken-3"
      class="pb-6"
    >
      <v-tabs-slider></v-tabs-slider>

      <v-tab href="#tab-1">
        Website
        <v-icon>mdi-desktop-classic</v-icon>
      </v-tab>

      <v-tab href="#tab-2">
        Document
        <v-icon>mdi-file-document</v-icon>
      </v-tab>
    </v-tabs>

    <v-tabs-items v-model="tab">
      <v-tab-item :value="'tab-1'">
        <v-row class="pt-4 pb-4">
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                height="200px"
              ></v-img>

              <v-card-title> Top western road trips </v-card-title>

              <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text> Explore </v-btn>
              </v-card-actions>
            </v-card> </v-col
          ><v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                height="200px"
              ></v-img>

              <v-card-title> Top western road trips </v-card-title>

              <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text> Explore </v-btn>
              </v-card-actions>
            </v-card> </v-col
          ><v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                height="200px"
              ></v-img>

              <v-card-title> Top western road trips </v-card-title>

              <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                height="200px"
              ></v-img>

              <v-card-title> Top western road trips </v-card-title>

              <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-tab-item>
      <v-tab-item :value="'tab-2'">
        <v-row class="pt-4 pb-4">
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://ph02.tci-thaijo.org/public/journals/273/cover_issue_16756_en_US.jpg"
                height="200px"
              ></v-img>

              <v-card-title>
                Sugar Cane Red Stripe Disease Detection using YOLO CNN of Deep
                Learning Technique</v-card-title
              >

              <v-card-subtitle>
                Vol. 8 No. 2 (2022): July - December
              </v-card-subtitle>

              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                  
                >
                  View
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-tab-item>
    </v-tabs-items>
  </div>
</template>
<script>
export default {
  data() {
    return {
      tab: null,
      text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.",
    };
  },
};
</script>
