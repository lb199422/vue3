<template>
  <div class="home">
    {{ msg }}
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  name: "Home",
  components: {},
  setup() {
    let msg = ref("this is home");
    return {
      msg,
    };
  },
};
</script>
