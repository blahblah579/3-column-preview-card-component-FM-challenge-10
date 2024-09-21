<template>
  <v-container>
    <v-row class="d-flex flex-column flex-md-row justify-center align-center my-10">
      <v-col cols="8" sm="5" md="4" class="i1 px-7">
        <v-col class="image mt-5">
          <img src="/src/assets/icon-sedans.svg" alt="" />
        </v-col>
        <v-col class="heading">SEDANS</v-col>
        <v-col class="para mt-1 mb-14"
          >Choose a sedan for its affordability and excellent fuel economy.
          Ideal for cruising in the city or on your next road trip.</v-col
        >
        <v-col class="mb-6">
          <v-btn rounded="xl" flat class="btn1 text-capitalize"
            >Learn More</v-btn
          >
        </v-col>
      </v-col>

      <v-col cols="8" sm="5" md="4" class="i2 px-7">
        <v-col class="image mt-5">
          <img src="/src/assets/icon-suvs.svg" alt="" />
        </v-col>
        <v-col class="heading">SUVS</v-col>
        <v-col class="para mt-1 mb-14"
          >Take an SUV for its spacious interior, power, and versatility.
          Perfect for your next family vacation and off-road adventures.</v-col
        >
        <v-col class="mb-6">
          <v-btn rounded="xl" flat class="btn2 text-capitalize"
            >Learn More</v-btn
          >
        </v-col>
      </v-col>

      <v-col cols="8" sm="5" md="4" class="i3 px-7">
        <v-col class="image mt-5">
          <img src="/src/assets/icon-luxury.svg" alt="" />
        </v-col>
        <v-col class="heading">LUXURY</v-col>
        <v-col class="para mt-1 mb-14"
          >Cruise in the best car brands without the bloated prices. Enjoy the
          enhanced comfort of a luxury rental and arrive in style.</v-col
        >
        <v-col class="mb-6">
          <v-btn rounded="xl" flat class="btn3 text-capitalize"
            >Learn More</v-btn
          >
        </v-col>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
@font-face {
  font-family: f1;
  src: url(/src/assets/BigShouldersDisplay-Bold.ttf);
}
@font-face {
  font-family: f2;
  src: url(/src/assets/LexendDeca-Regular.ttf);
}
.heading {
  font-family: f1;
  font-size: 40px;
  color: hsl(0, 0%, 95%);
}
.para {
  color: hsla(0, 0%, 100%, 0.75);
}
.i1 {
  background-color: hsl(30, 77%, 52%);
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
  border-top-right-radius: 0px;
  border-bottom-right-radius: 0px;
}
.i2 {
  background-color: hsl(185, 98%, 23%);
}
.i3 {
  background-color: #00403f;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  border-top-left-radius: 0px;
  border-bottom-left-radius: 0px;
}
.btn1 {
  background-color: white;
  color: hsl(30, 77%, 52%);
  box-sizing: border-box;
  border: 2px solid transparent;
  font-family: f2;
}

.btn1:hover {
  background-color: hsl(30, 77%, 52%);
  color: white;
  border: 1.5px solid white; /* Add a border for a cleaner look */
}

.btn2 {
  background-color: white;
  color: hsl(185, 98%, 23%);
  box-sizing: border-box;
  border: 2px solid transparent;
  font-family: f2;
}

.btn2:hover {
  background-color: hsl(185, 98%, 23%);
  color: white;
  border: 1.5px solid white; /* Add a border for a cleaner look */
}

.btn3 {
  background-color: white;
  color: #00403f;
  box-sizing: border-box;
  border: 2px solid transparent;
  font-family: f2;
}

.btn3:hover {
  background-color: #00403f;
  color: white;
  border: 1.5px solid white; /* Add a border for a cleaner look */
}
@media screen and (max-width: 959.98px) {
  .i1 {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
  }

  .i3 {
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    border-top-left-radius: 0;
    border-top-right-radius: 0;
  }
}

</style>