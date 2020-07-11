<template>
    <div class="container">
        <h1>Pokedex</h1>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
  @import url('https://fonts.googleapis.com/css?family=Acme');
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 10px;
    width: calc(100% - 20px);
    min-height: calc(100vh - 20px);
    background: radial-gradient(#156F99, #0A2E50);
    font-family: 'Acme', arial;
    font-size: 1rem;
    font-weight: normal;
  }
  h1 { color: #efefef; }
</style>