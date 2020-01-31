<template>
  <div>
    <p>Tstup {{msg}}</p>
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