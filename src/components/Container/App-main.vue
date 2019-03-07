<template>
  <main>
    <section-welcome></section-welcome>
    <section-offer></section-offer>
    <section-news></section-news>
    <section-experts></section-experts>
    <section-contact></section-contact>
  </main>
</template>

<script>
import sWelcome from './App-main/Section-welcome.vue';
import sOffer from './App-main/Section-offer.vue';
import sNews from './App-main/Section-news.vue';
import sExperts from './App-main/Section-experts.vue';
import sContact from './App-main/Section-contact.vue';

export default {
  components: {
    'section-welcome': sWelcome,
    'section-offer': sOffer,
    'section-news': sNews,
    'section-experts': sExperts,
    'section-contact': sContact
  }
}
</script>

<style lang="scss">
main{
  width: 100%;
  min-height: 600px;
}

.top-bar{
  height: 15px;
  border-bottom-left-radius: 10px;
  border-bottom-right-radius: 10px;
  background: hsl(230, 80%, 40%);
}

.section-header{
  padding: 20px;

  h2{
    margin: 0;
  }

  h6{
    margin: 0;
  }
}

</style>
