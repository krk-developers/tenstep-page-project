<template>
  <section class="section-offer">
    <div class="top-bar"></div>
    <div class="offer-header section-header">
      <h2>Oferta</h2>
      <h6>Wkrocz z nami w lepszy biznes.</h6>
    </div>
    <div class="offer-text">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus viverra laoreet viverra. Maecenas dignissim dui nunc, quis pharetra ligula tempus sed. Donec ullamcorper nibh et pellentesque ultricies. Nulla nec vulputate nulla. Phasellus luctus enim in sodales feugiat. Curabitur molestie orci id nulla tempus elementum. Etiam lectus sapien, blandit et dictum sit amet, aliquam at orci. Vestibulum auctor quis justo ac posuere. Maecenas nec urna justo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Ut lectus ex, suscipit vitae dui ut, iaculis dignissim nisl. Fusce euismod volutpat nibh nec eleifend. Donec sit amet elit finibus, scelerisque nulla et, aliquet mauris. Praesent id risus tortor. Nam interdum rhoncus mi, id rhoncus nulla tempor sit amet. Aliquam sapien nunc, porttitor quis maximus in, rhoncus sed tortor.</p>
    </div>
    <div class="offer-content"></div>
  </section>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
.section-offer{
  background: lightgray;
}

.offer-text{
  padding:20px;

  p{
    column-count: 2;
  }
}

.offer-content{
  height: 500px;
  background: hsl(30, 80%, 60%);
  margin-bottom: 30px;
}

</style>