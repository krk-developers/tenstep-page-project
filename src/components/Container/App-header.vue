<template>
  <header>
    <div class="header-title">
      <h1>Klinika Biznesu</h1>
      <h3>Leczymy dużych - Rozwijamy małych</h3>
    </div>
    <div class="header-content"></div>
  </header>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
header{
  width: 100%;
  height: 600px;
  background: hsl(320, 40%, 70%);
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-template-rows: repeat(6, 1fr);
  padding-bottom: 10px;
}

.header-title{
  padding: 20px;
  grid-column: 2/5;
  grid-row: 2/4;


  h1{
    display: inline-block;
    width: 310px;
    margin: 0 0 4px 0;;
    border-bottom: 1px solid #000;
    text-align: center;
  }

  h3{
    display: inline-block;
    width: 310px;
    margin: 0;
    border-top: 1px solid #000;
    text-align: center;
  }
}

.header-content{
  width: 800px;
  height: 300px;
  background: hsl(230, 80%, 40%);
  grid-column: 3/10;
  grid-row: 4/7;
}

</style>
