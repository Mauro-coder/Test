<template>
  <div>
    <p>Hi {{msg}}</p>
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