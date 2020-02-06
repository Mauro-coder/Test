<template>
  <div>
    <p>Hello {{msg}}</p>
  </div>
</template>

<script>
export default {
  name: "ComponentSayHi",
  props: {
    msg: String
  }
};
</script>

<style>
body {
  background-color: steelblue;
}
</style>
