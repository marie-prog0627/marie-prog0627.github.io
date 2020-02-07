<template>
  <v-container>
    <v-layout
      text-left
      wrap
      align-center
    >
      <v-flex xs3>
        <v-img
          :src="require('../assets/icon.svg')"
          class="my-3"
          contain
          height="200"
        ></v-img>

      </v-flex>

      <v-flex
        xs8
        mb-5
      >
        <h1 class="display-2 font-weight-bold mb-3">
          Profile
        </h1>
        <p class="subheading font-weight-bold">
          I am Ryota Sakuma, a student in College of Information Science, University of Tsukuba.
          <br>I research about haptics and develop support systems using haptic technology for people with impairments.
        </p>
      </v-flex>

      <v-flex
        xs12
        mb-5
      >
        <h2 class="headline font-weight-bold mb-3">Achievement</h2>
        <ul class="subheading font-weight-bold">
          <li>2019.12 Send my project to an exhibition, "装置とは限らない"</li>
          <li>2019.10 Released a paper at UIST 2019 posters</li>
          <li>2019.07 Released a paper at Work in Progress of World Haptics Conference 2019</li>
          <li>2018.12 Presented a poster at HCG 2018 (Domestic Conference)</li>
        </ul>
      </v-flex>
      <v-flex
        mb-5
        xs12
      >
        <h2 class="headline font-weight-bold mb-3">History</h2>

        <ul class="subheading font-weight-regular">
          <li>2018.03 Graduated from Kaichi high school</li>
          <li>2018.04 Entered Colleage of Information Science, University of Tsukuba</li>
        </ul>
      </v-flex>

      <v-flex
        xs12
        mb-5
      >
        <h2 class="headline font-weight-bold mb-3">Researches</h2>
        <p class = "subheading font-weight-regular">
          Work in Progress
        </p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'MyHome',
};
</script>
