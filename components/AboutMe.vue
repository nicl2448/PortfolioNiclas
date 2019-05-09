<template>
  <section
    id="about"
    class="hide-overflow"
  >
    <v-layout white>
      <v-flex
        xs12
        md6
        pa-5
      >
        <base-bubble-1
          style="transform: translate(5%, -5%)"
        />
        <base-heading class="info--text">
          Lidt om mig
        </base-heading>

        <base-text class="mb-5">
         Mit navn er Niclas, jeg er 23 og til dagligtlæser jeg multimediedesigner på ErhvervsAkademiet sydvest.<br>
         Det betyder også at jeg i hverdagen får lov at bruge og udvide mine kompitencer inde for Adobe programmerne og i front end kodning.<br>
         ud over det jeg laver med studiet er jeg meget social og elsker at give folk et godt grin. vil du læse mere så tryk på knappen ned for.
       <template>
  <div class="text-xs-center">
    <v-dialog
      v-model="dialog"
      width="500"
    >
      <template v-slot:activator="{ on }">
        <v-btn
          color="info"
          dark
          v-on="on"
        >
          Læs mit CV her 
        </v-btn>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Privacy Policy
        </v-card-title>

        <v-card-text>
        
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
        <v-img
          :src="require('@/assets/CV.png')"
        ></v-img>
         
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
</template>
        </base-text>


          
        
        
          <v-layout
            v-for="(skill, i) in skills"
            :key="i"
            style="color: #69A1BB;"
            wrap
          >
            <v-flex
              xs6
              text-uppercase
              v-text="skill.name"
            />
          
            
          </v-layout>
        
      </v-flex>
      
        <v-img
          :src="require('@/assets/velkommen.png')"
          height="100%"
        />
        
      
    </v-layout>
    
  </section>
</template>


<script>
  export default {
    data () {
      return {
        dialog: false
      }
    }
  }
</script>