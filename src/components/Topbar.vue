<template>
  <div class="topbar">{{ systemName }}</div>
</template>

<script>
import { mapGetters } from "vuex";

export default {
  name: "Topbar",
  data() {
    return {
      systemName: "systemName",
    };
  },
  computed: {},
  methods: {},
};
</script>
