<template>
  <div id="app">
    <h1>Gretengs app</h1>
    <input v-model="box" placeholder="Type your name here">
    <ComponentSayHi msg="box"/>
  </div>
</template>

<script>
import ComponentSayHi from "./components/ComponentSayHi";

export default {
  name: "App",
  components: {
    ComponentSayHi
  }
};
</script>