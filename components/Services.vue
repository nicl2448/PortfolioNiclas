<template>
  <section
    id="services"
    class="hide-overflow"
  >
    <v-layout accent>
      <v-flex
        hidden-sm-and-down
        md6
      >
        <VImg
          :src="require('@/assets/projekt.png')"
          height="100%"
        />
      </v-flex>
      <v-flex
        xs12
        md6
        text-xs-center
        pa-5
      >
        <v-layout
          align-center
          justify-center
          fill-height
          wrap
        >
          <v-flex xs12>
            <base-bubble-2
              style="transform: translateX(55%)"
            />
            <base-heading class="info--text">
              Kompitencer
            </base-heading>

            <base-text class="mb-5">
              Her er et lille udpluk af hvad jeg mener<br>
              er 4 af mine egne spidskompitencer.
            </base-text>
          </v-flex>
          <v-flex
            v-for="(service, i) in services"
            :key="i"
            md6
            text-xs-center
            mb-3
          >
            <v-avatar
              class="elevation-6 mb-2"
              color="#69A1BB"
              size="64"
              tile
            >
              <v-icon
                dark
                size="52"
                v-text="service.icon"
              />
            </v-avatar>
            <base-text>
              <div
                class="mb-2"
                v-text="service.name"
              />
              <div v-html="service.blurb" />
            </base-text>
          </v-flex>
        </v-layout>
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {
  data: () => ({
    services: [
      {
        name: 'Fælleskab',
        icon: 'mdi-clipboard-text-outline',
        blurb: 'Jeg gør altid meget ud af at være en del af fælleskabet og få folk til at grine og være glade '
      },
      {
        name: 'Tænking',
        icon: 'mdi-pencil-outline',
        blurb: 'Har altid være innovativ tænkende og kommet med gode idéer på løsning.'
      },
      {
        name: 'Køligt hoved',
        icon: 'mdi-settings-outline',
        blurb: 'Jeg er god til at holde hovedet koldt i pressede situationer.'
      },
      {
        name: 'punktlig',
        icon: 'mdi-home',
        blurb: 'Jeg gør altid meget ud af og være i god tid og også gerne være steder god tid.'
      }
    ]
  })
}
</script>
