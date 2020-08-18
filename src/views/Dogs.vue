<template>
  <div>
    <h1>Cats for adoption</h1>
    <b-table striped hover :items="dogs"></b-table>
  </div>
</template>

<script>
import { mapState } from "vuex";

export default {
  data() {
    return {};
  },
  computed: {
    ...mapState(["dogs"])
  }
};
</script>
