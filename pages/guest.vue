<template>
  <div>
    <h2>guest us</h2>
    <div v-for="guest in AllGuest" :key="guest.id">
      <h3>{{ guest.name }}</h3>
      <p>{{ guest.email }}</p>
    </div>
  </div>
</template>

<script>
import { mapGetters, mapActions } from "vuex";
export default {
  name: "guest",
  methods: {
    ...mapActions(["fetchGuest"]),
  },
  computed: mapGetters(["allGuests"]),
  created() {
    this.fetchGuest();
  },
};
</script>

<style scoped>
</style>