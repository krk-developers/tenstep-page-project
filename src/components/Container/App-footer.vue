<template>
  <footer>
    <div class="footer-logos">
      <span>Logo</span>
      <span>Logo</span>
      <span>Logo</span>
      <span>Logo</span>
      <span>Logo</span>
      <span>Logo</span>
    </div>
    <div class="footer-content"></div>
  </footer>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  footer{
    width: 100%;
    color: #fff;
  }

.footer-logos{
  height: 170px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background: #252525;

  span{
    padding: 20px 15px;
    background: hsl(120, 40%, 30%);
  }
}

.footer-content{
  height: 100px;
  background: #020202;
}

</style>
