<template>
  <section class="section-welcome">
    <div class="top-bar"></div>
    <div class="welcome-header">
      <h2>Witamy w TenStep</h2>
      <h6>Sprawdź co możemy dla ciebie zrobić.</h6>
    </div>
    <div class="welcome-body">
      <p><span class="bold">Lorem ipsum</span> dolor sit amet, consectetur adipiscing elit. Phasellus viverra laoreet viverra. Maecenas dignissim dui nunc, quis pharetra ligula tempus sed. Donec ullamcorper nibh et pellentesque ultricies. Nulla nec vulputate nulla. Phasellus luctus enim in sodales feugiat. Curabitur molestie orci id nulla tempus elementum.</p>
      <p>Etiam lectus sapien, blandit et dictum sit amet, aliquam at orci. Vestibulum auctor quis justo ac posuere. Maecenas nec urna justo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Ut lectus ex, suscipit vitae dui ut, iaculis dignissim nisl. Fusce euismod volutpat nibh nec eleifend. Donec sit amet elit finibus, scelerisque nulla et, aliquet mauris. Praesent id risus tortor. Nam interdum rhoncus mi, id rhoncus nulla tempor sit amet. Aliquam sapien nunc, porttitor quis maximus in, rhoncus sed tortor.</p>
    </div>
  </section>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
.section-welcome{
  padding-bottom: 30px;
}

.top-bar{
  height: 15px;
  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;
  background: hsl(230, 80%, 40%);
}

.welcome-header{
  padding: 20px;

  h2{
    margin: 0;
  }

  h6{
    margin: 0;
  }
}

.welcome-body{
  display: flex;
  padding: 15px;

  p{
    padding: 0 10px;

    .bold{
      font-weight: 700;
    }
  }
}
</style>