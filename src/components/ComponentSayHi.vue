<template>
  <div>
    <p>Hi {{msg}}</p>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      box: 'box'
    }
  },
  name: "ComponentSayHi",
  props: {
    msg: String
  }
};
</script>