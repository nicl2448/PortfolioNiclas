 <template>
  <v-container grid-list-md text-xs-center fluid>
        <base-heading class="info--text">
          Mine Projekter
        </base-heading>
    <v-layout row wrap>
        
     <!--CARD1!-->
 <v-flex  xs3>
        <v-card hover>
        <v-img
           :src="require('@/assets/projekt1.png')"
          aspect-ratio="1"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="info--text">Spas med Space</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

        <v-card-actions>
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
          Se Mere
        </v-btn>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Spas med Space
        </v-card-title>

        <v-card-text>
         Det her var vores projekt til vores 1.semester hvor vi skulle lave en hjemmeside med temaet "space". Der valgte min gruppe og jeg så at sætte et fokus på børn og vi kom frem til dette børnevenligt design.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            flat
            @click="dialog = false"
          >
            Ok
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
        </v-card-actions>

      </v-card>
        </v-flex>
 <!--CARD1slut!-->

 <!--CARD2!-->
        <v-flex  xs3>
        <v-card hover>
        <v-img
          :src="require('@/assets/project2.png')"
          aspect-ratio="1"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="info--text">SuperSuit</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

        <v-card-actions>
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
          Se Mere
        </v-btn>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Super Suit
        </v-card-title>

        <v-card-text>
          I dette projekt skue vi arbejde sammen med en anden studie linje. Vi skulle komme frem til et design til en et design til en webshop og så udvikle den. min gruppe valgte at lave en side der solgte ægte super suits og kom frem til dette design.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            flat
            @click="dialog = false"
          >
            Ok
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
        </v-card-actions>
      </v-card>
        </v-flex>
<!--CARD2slut!-->

<!--CARD3!-->
        <v-flex  xs3>
        <v-card hover>
        <v-img
           :src="require('@/assets/visitkort3.png')"
          aspect-ratio="1"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="info--text">Visitkort</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

        <v-card-actions>
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
          Se Mere
        </v-btn>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Visitkort
        </v-card-title>

        <v-card-text>
        Mit visitkort er lavet ud fra at jeg godt kan lide lige linjer og et rent simpelt design. derfor er der hellere ikke meget på mit visitkort hverken af farve eller tekst.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            flat
            @click="dialog = false"
          >
            Ok
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
        </v-card-actions>
      </v-card>
        </v-flex>
<!--CARD3slut!-->

<!--CARD4!-->
        <v-flex  xs3>
        <v-card hover>
        <v-img
          :src="require('@/assets/neptune.png')"
          aspect-ratio="1"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="info--text">Logo</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

        <v-card-actions>
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
          Se Mere
        </v-btn>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Infographic
        </v-card-title>

        <v-card-text>
          Vi skulle lave en infographic om og jeg valgte at lave min om neptune og igen er det et meget simpelt og rent design hvor der ikke er meget tekst men der bliver fulgt nogle bestemte linjer. 
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            flat
            @click="dialog = false"
          >
            Ok
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
        </v-card-actions>
      </v-card>
        </v-flex>
<!--CARD4slut!-->

    </v-layout>
  </v-container>
</template>


