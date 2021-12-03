<template>
  <div id="app">    
    <router-view />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500&display=swap');

:root {
  --bg-body: hsl(226, 43%, 10%);
  --bg-card: hsl(235, 46%, 20%);
  --bg-card-user: hsl(246, 80%, 60%);
  --bg-card-work: hsl(15, 100%, 70%);
  --bg-card-play: hsl(195, 74%, 62%);
  --bg-card-study: hsl(348, 100%, 68%);
  --bg-card-exercise: hsl(145, 58%, 55%);
  --bg-card-social: hsl(264, 64%, 52%);
  --bg-card-selfcare: hsl(43, 84%, 65%);

  --txt-white: hsl(0, 0%, 100%);
  --txt-blue: hsl(235, 45%, 61%);
  --txt-soft-blue: hsl(236, 100%, 87%);

  --card-border-radius: 10px;

}
body {
  background: var(--bg-body);
}

h1, h2, h3, p, label, span {
  font-family: 'Rubik', sans-serif;
  font-size: 18px;
  font-weight: 300;
  color: var(--txt-white);
  letter-spacing: .5px;

}
p {
  margin: 1rem 0 0;
}
</style>
