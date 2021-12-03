<template>
  <div>
    <user-card></user-card>
  </div>
</template>

<style scoped lang="scss"></style>

<script>
import UserCard from "../components/UserCard.vue";
export default {
  name: "Dashboard",
  components: {
    UserCard,
  },
};
</script>
