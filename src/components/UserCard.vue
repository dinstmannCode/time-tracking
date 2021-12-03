<template>
  <div class="card-container">
    <div class="card-container__user">
      <img src="../assets/image-jeremy.png" alt="" />
      <p>Report for</p>
      <h1>Jeremy Robson</h1>
    </div>

    <div class="card-date">
      <p>Daily</p>
      <p>Weekly</p>
      <p>Monthly</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card-container {
  display: flex;
  flex-direction: column;
  max-width: 230px;
  background: var(--bg-card);
  border-radius: var(--card-border-radius);

  &__user {
    background-color: var(--bg-card-user);
    border-radius: var(--card-border-radius);
    padding: 1.5rem;

    img {
      width: 25%;
      border: 1px solid #ffffff;
      border-radius: 50%;
    }

    p {
      color: var(--txt-soft-blue);
      font-size: 14px;
    }

    h1 {
      font-size: 32px;
    }
  }

  .card-date {
    padding: 1.5rem;

    p {
      color: var(--txt-blue);
      font-weight: 400;

      &:hover {
        cursor: pointer;
        color: var(--txt-white);
      }
    }
  }
}
</style>

<script>
export default {
  name: "UserCard",
};
</script>
