<template>
  <div>
    <user-card></user-card>
    <task-card></task-card>
  </div>
</template>

<style scoped lang="scss">
div {
  max-width: 960px;
  display: flex;
  justify-content: space-evenly;
}
</style>

<script>
import UserCard from "../components/UserCard.vue";
import TaskCard from "../components/TaskCard.vue";

export default {
  name: "Dashboard",
  components: {
    UserCard,
    TaskCard
  },
};
</script>
