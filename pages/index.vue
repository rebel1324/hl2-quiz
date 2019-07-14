<template>
  <section class="container">
    <div>
      <img src="hl2.svg" alt="">
      <h1 class="title">
        Half-Life 2 Sound Quiz
      </h1>
      <h2 class="subtitle">
        Find out how obessed and fucked up you are.
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Start Quiz</a>
      </div>
    </div>
  </section>
</template>

<script>
  const quotes = [
    "Find out how VALVE brainwashed your mind",
    "Find out how obessed and fucked up you are."
  ]
</script>

<style>
body {
  background: #292929
}

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: url('/haya.png')
}

.title {
  font-family: "Noto Sans", sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #fafafa;
  letter-spacing: 1px;
}

.subtitle {
  font-family: "Noto Sans", sans-serif; /* 1 */
  font-weight: 300;
  font-size: 42px;
  color: #fafafa;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

