<template>
  <div id="app">
    <h1>Greetings App</h1>
    <input v-model="box" placeholder="Type your name here">
    <ComponentSayHi :msg="box"/>
  </div>
</template>

<script>
import ComponentSayHi from "./components/ComponentSayHi";

export default {
  name: "App",
  data: function() {
    return {
      box: "Dude"
    };
  },
  components: {
    ComponentSayHi
  }
};
</script>