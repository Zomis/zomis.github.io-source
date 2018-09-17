<template>
  <v-container fluid>
    <v-slide-y-transition mode="out-in">
      <v-layout column align-center>
        <img src="@/assets/logo.png" alt="Vuetify.js" class="mb-5">
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
        <div>
          <a href="https://stackoverflow.com/users/1310566/simon-forsberg">
            <img src="https://stackoverflow.com/users/flair/1310566.png" width="208" height="58" alt="profile for Simon Forsberg at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Simon Forsberg at Stack Overflow, Q&amp;A for professional and enthusiast programmers">
          </a>
          <a href="https://codereview.stackexchange.com/users/31562/simon-forsberg">
            <img src="https://codereview.stackexchange.com/users/flair/31562.png" width="208" height="58" alt="profile for Simon Forsberg at Code Review Stack Exchange, Q&amp;A for peer programmer code reviews" title="profile for Simon Forsberg at Code Review Stack Exchange, Q&amp;A for peer programmer code reviews">
          </a>
          <a href="https://stackexchange.com/users/1376679">
            <img src="https://stackexchange.com/users/flair/1376679.png" width="208" height="58" alt="profile for Simon Forsberg on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Simon Forsberg on Stack Exchange, a network of free, community-driven Q&amp;A sites">
          </a>
        </div>


        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg" aspect-ratio="2.75"></v-img>
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-0">Minesweeper Flags Extreme</h3>
              <div>Online multiplayer game since 2008.</div>
            </div>
          </v-card-title>
          <v-card-actions>
            <v-btn href="http://www.minesweeperflags.net" flat color="orange">More info</v-btn>
          </v-card-actions>
        </v-card>
        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg" aspect-ratio="2.75"></v-img>
          <v-card-title primary-title>
            <div>
              <h3 class="headline mb-0">Zomis on GitHub</h3>
              <div>More than 40 repositories of fun stuff!</div>
            </div>
          </v-card-title>
          <v-card-actions>
            <v-btn href="http://www.github.com/Zomis" flat color="orange">Explore</v-btn>
          </v-card-actions>
        </v-card>
        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg" aspect-ratio="2.75"></v-img>
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
      </v-layout>
    </v-slide-y-transition>
  </v-container>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
