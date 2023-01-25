<template>
  <div>
    <v-col class="text-center">
      <h1 style="color: #424242; padding: 8px">About Me</h1>
      <p style="color: grey; padding: 8px">My Introdruction</p>
    </v-col>
    <v-row class="pt-4 pb-10">
      <v-col cols="12" sm="6" md="6" class="text-center">
        <v-card class="mx-auto" width="500" elevation="5">
          <!-- <v-img
            class="white--text align-end"
            height="300px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          >
          </v-img> -->
          <v-carousel
            hide-delimiters
            cycle
            show-arrows-on-hover
            height="300px"
          >
            <v-carousel-item
              v-for="(item, i) in items"
              :key="i"
              :src="item.src"
            ></v-carousel-item>
          </v-carousel>
        </v-card>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-row>
          <v-col cols="6" sm="6">
            <v-hover v-slot="{ hover }" close-delay="200">
              <v-card
                :elevation="hover ? 16 : 2"
                :class="{ 'on-hover': hover }"
                class="mx-auto"
                height="110"
                width="180"
              >
                <v-col class="text-center">
                  <v-icon large> mdi-medal-outline </v-icon>
                  <v-card-text> 2 + years </v-card-text>
                </v-col>
              </v-card>
            </v-hover>
          </v-col>

          <v-col cols="6" sm="6">
            <v-hover v-slot="{ hover }" close-delay="200">
              <v-card
                :elevation="hover ? 16 : 2"
                :class="{ 'on-hover': hover }"
                class="mx-auto"
                height="110"
                width="180"
              >
                <v-col class="text-center">
                  <v-icon large> mdi-briefcase-check-outline </v-icon>
                  <v-card-text color="grey"> 10 + Projects </v-card-text>
                </v-col>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="12" sm="12">
            <p style="color: grey; padding: 8px">
              Working on forntend developer of the system in the
              platform, website, line liff, Responsive web. About online
              shopping and a system to track the work of people within the
              company.
            </p>
          </v-col>
        </v-row>
      </v-col>
    </v-row>

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
        Educations
        <v-icon>mdi-school</v-icon>
      </v-tab>

      <v-tab href="#tab-2">
        Experience
        <v-icon>mdi-briefcase-arrow-up-down</v-icon>
      </v-tab>
    </v-tabs>

    <v-tabs-items v-model="tab">
      <v-tab-item :value="'tab-1'">
        <v-card class="mx-auto" width="800" elevation="0">
          <v-timeline>
            <v-timeline-item large>
              <template v-slot:icon>
                <v-avatar>
                  <img
                    src="~/assets/f2.jpg"
                  />
                </v-avatar>
              </template>
              <template v-slot:opposite>
                <span>High school </span>
              </template>
              <v-card class="elevation-2">
                <v-card-title class="">
                  Cheang Yuan Pittayakom School
                </v-card-title>
                <v-card-text>Math-Science </v-card-text>
              </v-card>
            </v-timeline-item>
            <v-timeline-item large>
              <template v-slot:icon>
                <v-avatar>
                  <img
                    src="~/assets/f2.jpg"
                  />
                </v-avatar>
              </template>
              <template v-slot:opposite>
                <span>Bachelor’s Degree </span>
              </template>
              <v-card class="elevation-2">
                <v-card-title class="">
                  Rajamangala University of Technology Isan Khonkaen Campus
                </v-card-title>
                <v-card-text>Computer Engineering</v-card-text>
              </v-card>
            </v-timeline-item>
          </v-timeline>
        </v-card>
      </v-tab-item>
      <v-tab-item :value="'tab-2'">
        <v-card class="mx-auto" width="800" elevation="0">
          <v-timeline>
            <v-timeline-item large>
              <template v-slot:icon>
                <v-avatar>
                  <img
                    src="~/assets/f2.jpg"
                  />
                </v-avatar>
              </template>
              <template v-slot:opposite>
                <span>2021 (intern)</span>
              </template>
              <v-card class="elevation-2">
                <v-card-title class=""> KhonKean Univercity </v-card-title>
                <v-card-text>Programmer</v-card-text>
              </v-card>
            </v-timeline-item>
            <v-timeline-item large>
              <template v-slot:icon>
                <v-avatar>
                  <img
                    src="~/assets/f2.jpg"
                  />
                </v-avatar>
              </template>
              <template v-slot:opposite>
                <span>2021 - 2022</span>
              </template>
              <v-card class="elevation-2">
                <v-card-title class="">
                  Morange solution MGC Electrotechno (Thailand).Co.,Ltd
                </v-card-title>
                <v-card-text>Front-End Developer</v-card-text>
              </v-card>
            </v-timeline-item>
            <v-timeline-item large>
              <template v-slot:icon>
                <v-avatar>
                  <img
                    src="~/assets/f2.jpg"
                  />
                </v-avatar>
              </template>
              <template v-slot:opposite>
                <span>2022 - Present</span>
              </template>
              <v-card class="elevation-2">
                <v-card-title class="">
                  MGC Electrotechno (Thailand).Co.,Ltd
                </v-card-title>
                <v-card-text>IT Staff</v-card-text>
              </v-card>
            </v-timeline-item>
          </v-timeline>
        </v-card>
      </v-tab-item>
    </v-tabs-items>
    <div class="pa-4"></div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          src: 'https://cdn.pixabay.com/photo/2021/01/21/21/48/mountain-ranges-5938639_960_720.jpg',
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg",
        },
        {
          src: "https://cdn.pixabay.com/photo/2019/09/21/13/09/mauritius-4493878_960_720.jpg",
        },
        {
          src: "https://cdn.pixabay.com/photo/2015/09/04/17/40/sunset-922411_960_720.jpg",
        },
      ],
      tab: null,
      text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.",
    };
  },
};
</script>
