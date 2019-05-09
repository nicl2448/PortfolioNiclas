<template>
  <section
    id="welcome"
    class="hide-overflow"
  >
    <v-layout>
      <v-flex
        hidden-sm-and-down
        md6
      >
        <v-img
          :src="require('@/assets/logo.png')"
          max-height="100%"
        />
      </v-flex>

      <v-flex
        xs12
      
        align-content-space-between
        layout
        :pa-5="$vuetify.breakpoint.smAndDown"
        wrap
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs10
            md6
          >
            <base-heading>NiclasDesigns</base-heading>
            <base-text>
              velkommen til mit portfolio hvor jeg vil vise mine designs og fortælle
              om hvad jeg har af kompitencer inde for web development og design.<br>
             Igennem siden vil jeg fortælle hvem jeg er, hvordan 
             jeg er som person, mine interesser både inde for mit fag 
             men også i min fritid.
            </base-text>
          </v-flex>
        </v-layout>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-flex>
    </v-layout>
  </section>
</template>
