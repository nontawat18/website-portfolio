<template>
  <div>
    <v-row class="pt-4">
      <v-col cols="12" sm="6" md="6" class="text-center">
        <!-- <v-avatar size="250">
          <img
            alt="user"
            src="https://cdn.pixabay.com/photo/2020/06/24/19/12/cabbage-5337431_1280.jpg"
          />
        </v-avatar> -->
        <div class="container">
          <div class="box">
            <div class="spin-container">
              <div class="shape">
                <div class="bd"></div>
              </div>
            </div>
          </div>
        </div>
      </v-col>
      <v-col cols="12" sm="6" md="6" class="container">
        <v-row class="text-center">
          <v-col cols="12" sm="12" md="12">
            <h1 style="color: #424242; padding: 8px">Nontawat Wichapha</h1>
          </v-col>
          <v-col cols="12" sm="12" md="12">
            <strong style="color: grey; padding: 8px">
              - Web Developer -
            </strong>
          </v-col>
          <v-col cols="12" sm="12" md="12">
            <p style="color: grey; padding: 8px">
              Working on the design and development of the system in the
              platform, website, line liff, Responsive web. About online
              shopping and a system to track the work of people within the
              company.
            </p>
          </v-col>
          <v-col cols="12" sm="12" md="12">
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
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>
<style>
.box {
  width: 60vmin;
  height: 60vmin;
  border: 1px dashed rgba(255, 255, 255, 0.4);
  position: relative;
  padding-top: 50px;
  padding-bottom: 50px;
}
h1 {
  justify-content: center;
}
p {
  justify-content: center;
}
strong {
  justify-content: center;
}
.spin-container {
  width: 100%;
  height: 100%;
  animation: spin 12s ease-in-out infinite alternate;
  position: relative;
}
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.shape {
  width: 100%;
  height: 100%;
  transition: border-radius 1s ease-out;
  border-radius: 50% 40% 30% 60% / 50% 30% 70% 40%;
  animation: morph 8s ease-in-out infinite both alternate;
  position: absolute;
  overflow: hidden;
  z-index: 5;
}

.bd {
  width: 142%;
  height: 142%;
  position: absolute;
  left: -21%;
  top: -21%;
  background: url("~/assets/f2.jpg");
  background-size: 60%;
  background-position: center center;
  display: flex;
  color: #003;
  font-size: 5vw;
  font-weight: bold;
  align-items: center;
  justify-content: center;
  text-align: center;
  text-transform: uppercase;
  animation: spin 12s ease-in-out infinite alternate-reverse;
  opacity: 1;
  z-index: 2;
}

@keyframes morph {
  0% {
    border-radius: 40% 60% 60% 40% / 60% 30% 70% 40%;
  }
  100% {
    border-radius: 40% 60%;
  }
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}
</style>
