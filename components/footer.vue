<template>
  <v-footer
    width="max"
    height="full"
  >
    <v-card
      flat
      tile
      class="info lighten-1 white--text text-xs-center"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-3 white--text"
          icon
        >
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        <h4>spangsbjerg kirkevej 103 <br> Nicl2448@easv365.dk <br> (+45) 12 34 56 78 </h4>
      <a href="https://www.linkedin.com"><i class="fab fa-linkedin"></i></a>
      <a href="https://www.facebook.com"><i class="fab fa-facebook-square">  </i> </a>
      <a href="https://youtube.com"><i class="fab fa-youtube-square">  </i> </a>
      <a href="https://instagram.com"><i class="fab fa-instagram"></i></a>
      </v-card-text>
  
      <v-divider></v-divider>

      
    </v-card>
  </v-footer>
</template>

<style>
i{
  font-size: 25px;
  margin: 5px;
}
</style>

