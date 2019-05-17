<template>
  <v-container grid-list-xl class="first">
    <v-layout v-bind="binding">
      <v-flex xs12 first>
        <v-card color="white" class="black--text">
          <v-layout row>
            <v-flex xs5>
              <v-img :src="require('@/assets/project/PortfolioWebsite.jpg')" height="400"></v-img>
            </v-flex>
            <v-flex xs7>
              <v-card-title primary-title>
                <div>
                  <div class="headline">Portfolio website</div>
                  <div>Vue website</div>
                  <div>05-2019</div>
                </div>
              </v-card-title>
              <v-divider></v-divider>
              <v-card-text>
                Ik heb mijn portfolio website gemaakt met VueJS, als eerste had ik een met HTML en CSS gemaakt. Hier was ik niet tevreden over dus heb ik gekozen om een nieuwe portfolio te maken met VueJS. Ik had hiervoor al een beetje ervaring met VueJS maar ik wilde meer over VueJS leren.
                Tijdens het maken van deze website heb ik vooral geleerd over hoe ik componenten gebruik en hoe ik een website kan stylen met Vuetify.
              </v-card-text>
            </v-flex>
          </v-layout>
          <v-layout>
            <v-flex xs1></v-flex>
            <v-flex xs2 align-self-center>
              <v-card-text>
                <a href="https://github.com/Sweetpurple616/Portfolio-website">
                  <v-icon large color="black">fa-github</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs2 align-self-center>
              <v-card-text>
                <a href="https://www.zoedewaard.com/">
                  <v-icon large color="black">fa-mouse-pointer</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs1>
              <v-divider vertical></v-divider>
            </v-flex>
            <v-flex xs7 align-content-space-around>
              <v-layout row>
                <v-flex xs4>
                  <h3>Vue</h3>
                </v-flex>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <v-flex xs12>
        <v-card color="white" class="black--text">
          <v-layout>
            <v-flex xs5>
              <v-img :src="require('@/assets/project/MusicNowPlease.jpg')" height="400" contain></v-img>
            </v-flex>
            <v-flex xs7>
              <v-card-title primary-title>
                <div>
                  <div class="headline">MusicNowPlease</div>
                  <div>Android App</div>
                  <div>04-2019</div>
                </div>
              </v-card-title>
              <v-divider></v-divider>
              <v-card-text>Dit is een Android App die ik heb gemaakt. De App laat een evenement zien die er als eerste aankomt in een stad. Dit doe ik met de hulp van de API van Ticketmaster. De stad kan in de settings worden gekozen en wordt hier opgeslagen. Dit was de eerste keer dat ik een mobile App heb gemaakt. Dit project was vooral het kennis maken met Android studio en het leren van Kotlin.</v-card-text>
            </v-flex>
          </v-layout>
          <v-layout row>
            <v-flex xs1></v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://github.com/Sweetpurple616/MusicNowPlease">
                  <v-icon large color="black">fa-github</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://youtu.be/UzFxFO7Izmo">
                  <v-icon large color="red">fa-youtube</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs1>
              <v-divider vertical></v-divider>
            </v-flex>
            <v-flex xs7 align-content-space-around>
              <v-layout row>
                <v-flex xs4>
                  <h3>Android Studio</h3>
                </v-flex>

                <v-flex xs4>
                  <h3>Kotlin</h3>
                </v-flex>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <v-flex xs12>
        <v-card color="white" class="black--text">
          <v-layout>
            <v-flex xs5>
              <v-img :src="require('@/assets/project/Fullstack.jpg')" height="400" contain></v-img>
            </v-flex>
            <v-flex xs7>
              <v-card-title primary-title>
                <div>
                  <div class="headline">Project MEVN</div>
                  <div>Fullstack</div>
                  <div>01-2019</div>
                </div>
              </v-card-title>
              <v-divider></v-divider>
              <v-card-text>
                In dit project heb ik een REST webapplicatie gemaakt waarin je projecten kan aanmaken, bewerken en verwijderen. Als eerste heb ik een API gemaakt die volledig CRUD is met ExpressJS, MongoDB en NodeJS op een Ubuntu server.
                Daarna heb ik een front-end gemaakt in VueJS met NodeJS. Dit project was de eerste keer dat ik met ExpressJS en VueJS werkte.
              </v-card-text>
            </v-flex>
          </v-layout>
          <v-layout row>
            <v-flex xs1></v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://github.com/Sweetpurple616/ProjectFullstack/tree/Front-end">
                  <v-icon large color="black">fa-github</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://youtu.be/gmhu8uuaFIM">
                  <v-icon large color="red">fa-youtube</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs1>
              <v-divider vertical></v-divider>
            </v-flex>
            <v-flex xs7 align-content-space-around>
              <v-layout row>
                <v-flex xs4>
                  <h3>MongoDB</h3>
                </v-flex>
                <v-flex xs4>
                  <h3>ExpressJS</h3>
                </v-flex>
                <v-flex xs4>
                  <h3>VueJS</h3>
                </v-flex>
                <v-flex xs4>
                  <h3>NodeJS</h3>
                </v-flex>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <v-flex xs12>
        <v-card color="white" class="black--text">
          <v-layout>
            <v-flex xs5>
              <v-img :src="require('@/assets/project/sails.jpg')" height="400" contain></v-img>
            </v-flex>
            <v-flex xs7>
              <v-card-title primary-title>
                <div>
                  <div class="headline">SailsJS</div>
                  <div>MVC Framework</div>
                  <div>11-2018</div>
                </div>
              </v-card-title>
              <v-divider></v-divider>
              <v-card-text>In dit project heb ik een CRUD web applicatie gemaakt een MVC framework, hier heb ik SailsJS voor gebruikt. Op de web applicatie kan worden ingelogd. Je kan een foto uploaden en deze kunnen andere mensen raten. Met dit project heb ik vooral veel geleerd over mijzelf. Het framework was best wel lastig en het ging allemaal niet zo lekker. Ik heb geleerd dat ik enorm goed kan doorzetten. En logisch kan nadenken op momenten dat het niet zo goed lukt. Uiteindelijk is het niet helemaal gelukt om hem werkend te krijgen. Maar dit was minder belangrijk dat het leerproces.</v-card-text>
            </v-flex>
          </v-layout>
          <v-layout row>
            <v-flex xs1></v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://github.com/Sweetpurple616/Programmeren-5">
                  <v-icon large color="black">fa-github</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs2></v-flex>
            <v-flex xs1>
              <v-divider vertical></v-divider>
            </v-flex>
            <v-flex xs7 align-content-space-around>
              <v-layout row>
                <v-flex xs4>
                  <h3>SailsJS</h3>
                </v-flex>
                <v-flex xs4>
                  <h3>MySQL</h3>
                </v-flex>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>
      <v-flex xs12>
        <v-card color="white" class="black--text">
          <v-layout>
            <v-flex xs5>
              <v-img :src="require('@/assets/project/game1.jpg')" height="400" contain></v-img>
            </v-flex>
            <v-flex xs7>
              <v-card-title primary-title>
                <div>
                  <div class="headline">Ape of Divinity</div>
                  <div>Typescript/phaser game</div>
                  <div>06-2018</div>
                </div>
              </v-card-title>
              <v-divider></v-divider>
              <v-card-text>Dit is een groepsproject geweest, in dit project hebben we een leerzame game gemaakt voor kinderen. In onze game bestuur je een aapje die een avontuur beleeft terwijl hij de Griekse goden leert kennen. In dit project hebben we met PhaserJS en typescript gewerkt. In dit project was mijn taak vooral het programmeren. Ik heb verschillende delen geprogrammeerd zoals de functionaliteit van de speler tot aan het plaatsen van level elementen.</v-card-text>
            </v-flex>
          </v-layout>
          <v-layout row>
            <v-flex xs1></v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://github.com/IAmMisterFrank/CLE4">
                  <v-icon large color="black">fa-github</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs2></v-flex>
            <v-flex xs1>
              <v-divider vertical></v-divider>
            </v-flex>
            <v-flex xs7 align-content-space-around>
              <v-layout row>
                <v-flex xs4>
                  <h3>Typescript</h3>
                </v-flex>
                <v-flex xs4>
                  <h3>PhaserJS</h3>
                </v-flex>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>
      <v-flex xs12>
        <v-card color="white" class="black--text">
          <v-layout>
            <v-flex xs5>
              <v-img :src="require('@/assets/project/typescriptgame.jpg')" height="400" contain></v-img>
            </v-flex>
            <v-flex xs7>
              <v-card-title primary-title>
                <div>
                  <div class="headline">Typescript game</div>
                  <div>Typescript game</div>
                  <div>06-2018</div>
                </div>
              </v-card-title>
              <v-divider></v-divider>
              <v-card-text>Dit is een kleine game die ik heb gemaakt met Typescript. In de game bestuur jij een panda en het is de bedoeling dat je alle donuts opvangt. Elke donut is een punt, raakt de donut de onderkant dan ben je af. Daarnaast slaat die ook nog de Highscore op. Dit was de eerste keer dat ik een game heb geprogrammeerd en ook de eerste keer werken met Typescript.</v-card-text>
            </v-flex>
          </v-layout>
          <v-layout row>
            <v-flex xs1></v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="https://github.com/Sweetpurple616/PGRM04">
                  <v-icon large color="black">fa-github</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs2>
              <v-card-text>
                <a href="http://zoehey.nl/game/docs/">
                  <v-icon large color="black">fa-mouse-pointer</v-icon>
                </a>
              </v-card-text>
            </v-flex>
            <v-flex xs1>
              <v-divider vertical></v-divider>
            </v-flex>
            <v-flex xs7 align-content-space-around>
              <v-layout row>
                <v-flex xs4>
                  <h3>Typescript</h3>
                </v-flex>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  computed: {
    binding() {
      const binding = {}

      if (this.$vuetify.breakpoint.mdAndUp) binding.column = true

      return binding
    }
  }
}
</script>

<style>
.flex xs5 {
  padding: 0px;
}
.xs12 {
  margin-bottom: 50px;
}
.first {
  margin-top: -50px;
}
a {
  text-decoration: none;
}
</style>
