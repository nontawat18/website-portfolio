<template>
  <div>
    <v-col class="text-center">
      <h1 style="color: #424242; padding: 8px">About Me</h1>
      <p style="color: grey; padding: 8px">My Introdruction</p>
    </v-col>
    <v-row class="pt-4">
      <v-col cols="12" sm="6" md="6" class="text-center">
        <v-card class="mx-auto" width="500" elevation="5">
          <v-img
            class="white--text align-end"
            height="300px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          >
          </v-img>
          <!-- 
          <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

          <v-card-text class="text--primary">
            <div>Whitehaven Beach</div>

            <div>Whitsunday Island, Whitsunday Islands</div>
          </v-card-text>

          <v-card-actions>
            <v-btn color="orange" text> Share </v-btn>

            <v-btn color="orange" text> Explore </v-btn>
          </v-card-actions> -->
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
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit,
              cumque. Dolorem, odio neque vel dolore saepe, non quaerat,
              eligendi temporibus nisi veritatis repellendus reiciendis?
              Accusantium quo esse facere aliquam nobis!
            </p>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <v-col cols="12" sm="12" md="12" class="pt-16  text-center">
      <v-card class="mx-auto" width="800" elevation="0">
        <v-row>
          <v-col cols="12" sm="12" md="12">
            <v-icon large right> mdi-school </v-icon>
            <h1 style="color: #424242; padding: 8px">Educations</h1>
          </v-col>
        </v-row>
        <v-timeline>
          <v-timeline-item large>
            <template v-slot:icon>
              <v-avatar>
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/1/18/Choi_Soo-bin_%28%EC%B5%9C%EC%88%98%EB%B9%88%29_220121.jpg"
                />
              </v-avatar>
            </template>
            <template v-slot:opposite>
              <span>High school </span>
            </template>
            <v-card class="elevation-2">
              <v-card-title class="text-h5">
                Cheang Yuan Pittayakom School
              </v-card-title>
              <v-card-text>Math-Science </v-card-text>
            </v-card>
          </v-timeline-item>
          <v-timeline-item large>
            <template v-slot:icon>
              <v-avatar>
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/1/18/Choi_Soo-bin_%28%EC%B5%9C%EC%88%98%EB%B9%88%29_220121.jpg"
                />
              </v-avatar>
            </template>
            <template v-slot:opposite>
              <span>Bachelor’s Degree </span>
            </template>
            <v-card class="elevation-2">
              <v-card-title class="text-h5">
                Rajamangala University of Technology Isan Khonkaen Campus
              </v-card-title>
              <v-card-text>Computer Engineering</v-card-text>
            </v-card>
          </v-timeline-item>
        </v-timeline>
      </v-card>
    </v-col>
    <v-col cols="12" sm="12" md="12" class="pt-16  text-center">
      <v-card class="mx-auto" width="800" elevation="0">
        <v-row>
          <v-col cols="12" sm="12" md="12">
            <v-icon large right> mdi-briefcase-arrow-up-down </v-icon>
            <h1 style="color: #424242; padding: 8px">Experience</h1>
          </v-col>
        </v-row>
        <v-timeline>
          <v-timeline-item large>
            <template v-slot:icon>
              <v-avatar>
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/1/18/Choi_Soo-bin_%28%EC%B5%9C%EC%88%98%EB%B9%88%29_220121.jpg"
                />
              </v-avatar>
            </template>
            <template v-slot:opposite>
              <span>2021 (intern)</span>
            </template>
            <v-card class="elevation-2">
              <v-card-title class="text-h5">
               KhonKean Univercity
              </v-card-title>
              <v-card-text>Programmer</v-card-text>
            </v-card>
          </v-timeline-item>
          <v-timeline-item large>
            <template v-slot:icon>
              <v-avatar>
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/1/18/Choi_Soo-bin_%28%EC%B5%9C%EC%88%98%EB%B9%88%29_220121.jpg"
                />
              </v-avatar>
            </template>
            <template v-slot:opposite>
              <span>2021 - 2022</span>
            </template>
            <v-card class="elevation-2">
              <v-card-title class="text-h5">
                Morange solution MGC Electrotechno (Thailand).Co.,Ltd
              </v-card-title>
              <v-card-text>Front-End Developper</v-card-text>
            </v-card>
          </v-timeline-item>
          <v-timeline-item large>
            <template v-slot:icon>
              <v-avatar>
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/1/18/Choi_Soo-bin_%28%EC%B5%9C%EC%88%98%EB%B9%88%29_220121.jpg"
                />
              </v-avatar>
            </template>
            <template v-slot:opposite>
              <span>2022 - Present</span>
            </template>
            <v-card class="elevation-2">
              <v-card-title class="text-h5">
                MGC Electrotechno (Thailand).Co.,Ltd
              </v-card-title>
              <v-card-text>IT Staff</v-card-text>
            </v-card>
          </v-timeline-item>
        </v-timeline>
      </v-card>
    </v-col>
  </div>
</template>
<script>
export default {};
</script>
