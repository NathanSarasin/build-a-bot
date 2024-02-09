<template>
  <header>
    <nav>
      <ul>
        <li class="nav-item">
          <img class="logo" src="./assets/build-a-bot-logo.png" alt="logo" />
          Build-A-Bot
        </li>
      </ul>
    </nav>
  </header>
  <main>
  <!--<HomePage msg="Welcome to You vue.js app" /> -->
    <RobotBuilder></RobotBuilder>
  </main>
</template>

<script>
import RobotBuilder from './build/RobotBuilder.vue';

export default {
  name: 'App',
  components: {
    RobotBuilder,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}
main {
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width: 1400px;
  min-height: 300px;
}
</style>
