<template>
  <header>
      
  </header>
  <main>
      <container>
      </container>
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../styles/base.sass';

header {
    border: 1px solid black;
    grid-row: 5/7;
    grid-column: 2/7;

}

main {
    border: 1px solid red;
    grid-row: 7/11;
    grid-column: 2/7;
}

</style>