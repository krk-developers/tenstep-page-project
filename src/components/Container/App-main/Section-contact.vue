<template>
  <section class="section-contact">
    <div class="top-bar"></div>
    <div class="contact-header section-header">
      <h2>Kontakt</h2>
      <h6>Napisz do nas</h6>
    </div>
    <div class="contact-content">
      <contact-form></contact-form>
      <div class="contact-info">
        <h3>
          <span>Jeśli masz jakieś pytania, napisz</span>
          <span>Chętnie rozwiejemy Twoje wątpliwości.</span>
        </h3>
        <div class="contact-person">
          <div class="person-img"></div>
          <div class="person-info">
            <h5>Katarzyna Renn</h5>
            <p>Dyrektor operacyjny, trenerka, konsultantka. Jej "oczko w głowie" to dokumentacja i poprawność formalna realizowanych projektów. Zajmuje się też relacjami i rozliczeniami z klientami.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import contactForm from './Section-contact-form.vue';

export default {
  components:{
    'contact-form': contactForm
  }
}
</script>

<style lang="scss">
.section-contact{
  padding-bottom: 180px;
}

.contact-content{
  height: 400px;
  background: hsl(230, 60%, 53%);
  margin-top: 100px;
  position: relative;
  display: flex;
  flex-direction: row-reverse;

  .contact-info{
    width: 550px;
    height: 400px;
    margin-right: 200px;

    h3{
      margin: 80px 0 50px 0;
      
      span{
        display: block;
        color: #fff;
      }
    }

    .contact-person{
      background: #fff;
      display: flex;
      padding: 5px;

      .person-img{
        width: 100px;
        height: 100px;
        background: red;
        border-radius: 50%;
      }

      .person-info{

        margin-left: 20px;

        h5{
          font-size: 16px;
        }

        p{
          width: 400px;
          margin-top: 20px;
          font-size: 14px;
        }
      }
    }
  }
}

</style>