<template>
  <section class="authenticate-container">
    <main class="authenticate-content">
      <router-view />
    </main>
  </section>
</template>

<script>
export default {
  name: "Authenticate",
};
</script>

<style lang="scss" scoped>
.authenticate-container {
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;

  .authenticate-content {
    margin: 20px;
    box-sizing: border-box;
    background-color: #fff;
    width: 100%;
    max-width: 450px;
    min-height: 400px;
    padding: 70px 50px;
    border-radius: 5px;
    border-radius: var(--card-border-radius);
    box-shadow: var(--card-shadow);
  }
}
</style>