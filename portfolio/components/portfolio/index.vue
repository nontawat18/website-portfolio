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
        .Net
        <v-icon>mdi-dot-net</v-icon>
      </v-tab>
      <v-tab href="#tab-2">
        Nuxt.js
        <v-icon>mdi-nuxt</v-icon>
      </v-tab>
      <v-tab href="#tab-3">
        React.js
        <v-icon>mdi-react</v-icon>
      </v-tab>
      <v-tab href="#tab-4">
        Odoo
        <v-icon>mdi-code-tags</v-icon>
      </v-tab>
      <v-tab href="#tab-5">
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
                src="https://dotnet.microsoft.com/static/images/redesign/social/square.png"
                height="200px"
              ></v-img>

              <v-card-title> Check Sheet System</v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://dotnet.microsoft.com/static/images/redesign/social/square.png"
                height="200px"
              ></v-img>

              <v-card-title> IT Stock System </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://dotnet.microsoft.com/static/images/redesign/social/square.png"
                height="200px"
              ></v-img>

              <v-card-title> IP System</v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
        </v-row>
      </v-tab-item>
      <v-tab-item :value="'tab-2'">
        <v-row class="pt-4 pb-4">
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>KCM Logistics </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>KCM Rodtank Shop </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>PCOA Repair Products </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>PCOA Services </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>All Events </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>Credit Bank RMU </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>Unicon Concrete Shop</v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://miro.medium.com/max/1200/0*HsriGncgl-JOIbE0.png"
                height="200px"
              ></v-img>

              <v-card-title>Smart Track RMU</v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
        </v-row>
      </v-tab-item>
      <v-tab-item :value="'tab-3'">
        <!-- <v-row class="pt-4 pb-4">
          <v-col cols="12" sm="3" md="3">
            <v-card
              class="mx-auto"
              max-width="344"
              href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
              target="_blank"
            >
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
          <v-col cols="12" sm="3" md="3">
            <v-card
              class="mx-auto"
              max-width="344"
              href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
              target="_blank"
            >
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
          <v-col cols="12" sm="3" md="3">
            <v-card
              class="mx-auto"
              max-width="344"
              href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
              target="_blank"
            >
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
          <v-col cols="12" sm="3" md="3">
            <v-card
              class="mx-auto"
              max-width="344"
              href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
              target="_blank"
            >
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
        </v-row> -->
      </v-tab-item>
      <v-tab-item :value="'tab-4'">
        <v-row class="pt-4 pb-4">
          
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://www.odoo.com/web/image/website/1/social_default_image?unique=8f9cd72"
                height="200px"
              ></v-img>

              <v-card-title>PCOA Repair Products </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://www.odoo.com/web/image/website/1/social_default_image?unique=8f9cd72"
                height="200px"
              ></v-img>

              <v-card-title>PCOA Services </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://www.odoo.com/web/image/website/1/social_default_image?unique=8f9cd72"
                height="200px"
              ></v-img>

              <v-card-title>All Events </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://www.odoo.com/web/image/website/1/social_default_image?unique=8f9cd72"
                height="200px"
              ></v-img>

              <v-card-title>Credit Bank RMU </v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://www.odoo.com/web/image/website/1/social_default_image?unique=8f9cd72"
                height="200px"
              ></v-img>

              <v-card-title>Unicon Concrete Shop</v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
          <v-col cols="12" sm="3" md="3">
            <v-card class="mx-auto" max-width="344">
              <v-img
                src="https://www.odoo.com/web/image/website/1/social_default_image?unique=8f9cd72"
                height="200px"
              ></v-img>

              <v-card-title>Smart Track RMU</v-card-title>
              <!-- <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn
                  color="indigo darken-4"
                  text
                  href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
                  target="_blank"
                >
                  View
                </v-btn>
              </v-card-actions> -->
            </v-card>
          </v-col>
        </v-row>
      </v-tab-item>
      <v-tab-item :value="'tab-5'">
        <v-row class="pt-4 pb-4">
          <v-col cols="12" sm="3" md="3">
            <v-card
              class="mx-auto"
              max-width="344"
              href="https://ph02.tci-thaijo.org/index.php/mijet/article/view/244320"
              target="_blank"
            >
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
