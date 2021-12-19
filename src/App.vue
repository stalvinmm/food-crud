<template>
  <div>
    <foodtask />
  </div>
</template>

<script>
import foodtask from "./components/foodtask";

export default {
  name: "App",

  components: {
    foodtask,
  },

  data: () => ({
    //
  }),
};
</script>
