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
</style>
