<template>
  <v-container fluid>
    <v-slide-y-transition mode="out-in">
      <v-layout row wrap align-center justify-center>
        <img src="@/assets/simon.jpg" alt="Picture of Simon Forsberg" class="simon" />
        <!--
        <blockquote>
          &#8220;Something&#8221;
          <footer>
            <small>
              <em>&mdash;Simon Forsberg</em>
            </small>
          </footer>
        </blockquote>
        -->
        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Simon Forsberg</h3>
                <div>Who he is and what he's done</div>
              </div>
            </v-card-title>
            <v-card-text>If you want to connect with me on LinkedIn, please also add a message about how you found me. Did you listen to one of my talks perhaps?</v-card-text>
            <v-card-actions>
              <v-btn href="https://www.linkedin.com/in/simonforsberg/" flat color="blue">Connect</v-btn>
              <v-btn href="mailto:simon.forsberg@sigma.se" flat color="blue">Send e-mail</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>
        <v-flex xs12>
          <v-card class="flairs">
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Stack Exchange Network</h3>
                <div>Stack Overflow and Code Review Stack Exchange</div>
              </div>
            </v-card-title>
            <div class="flair">
              <a href="https://stackoverflow.com/users/1310566/simon-forsberg">
                <img
                  src="https://stackoverflow.com/users/flair/1310566.png"
                  width="208"
                  height="58"
                  alt="profile for Simon Forsberg at Stack Overflow, Q&amp;A for professional and enthusiast programmers"
                  title="profile for Simon Forsberg at Stack Overflow, Q&amp;A for professional and enthusiast programmers"
                />
              </a>
            </div>
            <div class="flair">
              <a href="https://codereview.stackexchange.com/users/31562/simon-forsberg">
                <img
                  src="https://codereview.stackexchange.com/users/flair/31562.png"
                  width="208"
                  height="58"
                  alt="profile for Simon Forsberg at Code Review Stack Exchange, Q&amp;A for peer programmer code reviews"
                  title="profile for Simon Forsberg at Code Review Stack Exchange, Q&amp;A for peer programmer code reviews"
                />
              </a>
            </div>
            <!--
          <div class="flair">
            <a href="https://stackexchange.com/users/1376679">
              <img src="https://stackexchange.com/users/flair/1376679.png" width="208" height="58" alt="profile for Simon Forsberg on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Simon Forsberg on Stack Exchange, a network of free, community-driven Q&amp;A sites">
            </a>
          </div>
            -->
            <v-card-actions>
              <v-btn
                href="https://stackoverflow.com/users/1310566/simon-forsberg"
                flat
                color="orange"
              >Stack Overflow</v-btn>
              <v-btn
                href="https://codereview.stackexchange.com/users/31562/simon-forsberg"
                flat
                color="blue"
              >Code Review</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>

        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Minesweeper Flags Extreme</h3>
                <div>Online multiplayer game since 2008. During its peak popularity, an average of one game was played per minute. Originally made in Flash and PHP, now using Java and LibGDX</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn href="https://www.minesweeperflags.net" flat color="orange">Play</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>
        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Zomis on GitHub</h3>
                <div>More than 50 repositories of fun stuff!</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn href="https://www.github.com/Zomis" flat color="orange">Explore</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>

        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">A bot named Duga</h3>
                <div>Webhook for Stack Exchange chat rooms and watches for comments.</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn
                href="https://codereview.stackexchange.com/users/51786/duga?tab=profile"
                flat
                color="orange"
              >Discover</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>

        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Zomis' Games</h3>
                <div>A flexible server and client supporting several games. Using Kotlin and Vue.</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn href="https://games.zomis.net/" flat color="orange">Play</v-btn>
              <v-btn href="https://github.com/Zomis/Server2" flat color="orange">More info</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>

        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Cardshifter</h3>
                <div>A collaboration project where Simon is/was the lead developer. Using Java, Groovy and Vue - previously used AngularJS.</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn href="https://cardshifter.zomis.net/" flat color="orange">Play</v-btn>
              <v-btn href="https://github.com/Cardshifter/Cardshifter" flat color="orange">More info</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>

        <v-flex xs12>
          <v-card>
            <v-card-title primary-title>
              <div>
                <h3 class="headline mb-0">Factorio Mods</h3>
                <div>Mods for the great automation game Factorio made by Simon.</div>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn href="https://mods.factorio.com/user/Zomis" flat color="orange">Explore</v-btn>
            </v-card-actions>
          </v-card>
        </v-flex>
      </v-layout>
    </v-slide-y-transition>
  </v-container>
</template>

<style scoped>
.v-card {
  max-width: 500px;
  margin-bottom: 42px;
  margin-left: auto;
  margin-right: auto;
}

.flair {
  margin-left: 15px;
}

.simon {
  height: 300px;
  margin-bottom: 20px;
  box-shadow: 10px 10px 10px #575757;
  border-radius: 500px;
}

h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
