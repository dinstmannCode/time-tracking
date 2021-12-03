<template>
  <div class="card-grid">
    <div>
      <h2>Work</h2>
      <p>32hrs</p>
      <p class="txt-previous">Previous - 36hrs</p>
    </div>

    <div>
      <h2>Work</h2>
      <p>32hrs</p>
      <p class="txt-previous">Previous - 36hrs</p>
    </div>

    <div>
      <h2>Work</h2>
      <p>32hrs</p>
      <p class="txt-previous">Previous - 36hrs</p>
    </div>

    <div>
      <h2>Work</h2>

      <p>32hrs</p>
      <p class="txt-previous">Previous - 36hrs</p>
    </div>

    <div>
      <h2>Work</h2>
      <p>32hrs</p>
      <p class="txt-previous">Previous - 36hrs</p>
    </div>

    <div>
      <h2>Work</h2>
      <p>32hrs</p>
      <p class="txt-previous">Previous - 36hrs</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  justify-items: center;

  div {
    background: var(--bg-card);
    border-radius: var(--card-border-radius);
    margin: 1rem;
    padding: 1.5rem;

    h2 {
      font-weight: 600;
    }

    p {
      font-size: 32px;
    }

    .txt-previous {
      color: var(--txt-soft-blue);
      font-size: 14px;
    }
  }
}
</style>

<script>
export default {
  name: "TaskCard",
};
</script>
