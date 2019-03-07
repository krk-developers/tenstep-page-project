<template>
  <form class="contact-form">
    <h5>Formularz kontaktowy</h5>
    <label class="label" for="">Imię i nazwisko</label>
    <input class="input" type="text" id="name">
    <label class="label" for="">E-mail</label>
    <input class="input" type="text" id="email">
    <label class="label" for="">Telefon</label>
    <input class="input" type="text" id="phone">
    <label class="label" for="">Treść wiadomości</label>
    <textarea class="textarea" id="message"></textarea>
    <button class="button">Wyślij</button>
  </form>
</template>

<style lang="scss">

.contact-form{
  width: 360px;
  display: flex;
  flex-direction: column;
  align-items: center;
  background: #fff;
  border: 1px solid lightgray;
  box-shadow: 0 0 12px 1px gray;
  padding: 20px 0 50px 0;
  position: absolute;
  top: -50px;
  left: 200px;

  h5{
    font-size: 20px;
    margin: 0;
  }

  .label{
    width: 240px;
    margin-top: 15px;
    font-size: 14px;
  }

  .input{
    width: 240px;
    height: 36px;
    border: 1px solid gray;
  }

  .textarea{
    width: 240px;
    height: 160px;
    border: 1px solid gray;
  }

  .button{
    width: 240px;
    height: 30px;
    border: 1px solid gray;
    background: #fff;
    margin-top: 20px;
    color: gray;
    font-weight: 700;
    font-size: 16px;
  }
  .button:hover{
    background: gray;
    color: #fff;
  }

}

</style>
