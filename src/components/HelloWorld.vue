<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>

    <div class="stackexchange-flair">
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

    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
