<template>
  <div>
    <section class="hero">
      <img class="hero__nootris" src="/Mask_Group.png">
      <h1 class="hero__title"> Активируй иммунитет!</h1>
      <div class="hero__description"> Всего пять секунд в день помогут укрепить иммунитет <br> и повысить
        защитные силы организма
      </div>
      <div class="hero__subtitle"> NOOTRIS ПОМОГАЕТ</div>
      <div class="hero__subdescription"> Вашему организму во время пандемии <br> и сезонных простуд</div>
    </section>
    <section class="offer">
      <div class="offer__title">
        ПОЛУЧИ ЗАЩИТУ ИММУНИТЕТА <br>
        <span class="offer__title_orange">СО СКИДКОЙ -15% ПЕРВЫМ!</span>
      </div>
      <div class="offer__price price">
        <span class="price__before">&nbsp;750₽&nbsp; </span>
        690₽
      </div>
    </section>
    <section class="advantage">
      <div>
        <img src="/ginger.png" class="advantage__art">
        <div class="advantage__title">Содержит</div>
        <div class="advantage__body">имбирь</div>
      </div>
      <div>
        <div>
          <img src="/nootris.png" class="advantage__art_main">
          <div class="advantage__title advantage__title_main"> + Бесплатная доставка</div>
          <div class="advantage__body advantage__body_main"> Специальная цена</div>
        </div>
      </div>
      <div>
        <img src="/vorus.png" class="advantage__art">
        <div class="advantage__title">Нейтрализует</div>
        <div class="advantage__body">вирусы</div>
      </div>
    </section>
    <section class="order">
      <div class="order__btn btn"> Оформить заказ!</div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style scoped>

.hero {
  background: url("/bg.png");
  position: relative;
  padding: 130px 60px 96px;
}

.hero__title {
  position: relative;
  font-style: normal;
  font-weight: 700;
  font-size: 144px;
  line-height: 152px;
  color: white;
  text-transform: uppercase;
  z-index: 100;
  padding-bottom: 24px;
  padding-top: 80px;
}

.hero__description {
  font-weight: 400;
  font-size: 24px;
  line-height: 28px;
  margin-bottom: 120px;
}

.hero__subtitle {
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 36px;
  margin-bottom: 16px;
}

.hero__subdescription {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}

.hero__nootris {
  position: absolute;
  left: 620px;
  top: 20px;
  z-index: 0;
}

.offer {
  margin-top: 110px;
}

.offer__title {
  color: white;
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 57px;
  text-align: center;
  margin-bottom: 85px;
}

.offer__title_orange {
  color: #FCB500;
}

.advantage {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  text-align: center;
  margin-bottom: 64px;
  font-size: 18px;
  line-height: 21px;
}

.offer__price {
  padding-bottom: 59px;
}

.price {
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 48px;
  line-height: 57px;
}

.price__before {
  text-decoration: line-through;
  color: #ADADAD;
  font-size: 36px;
  line-height: 43px;
  padding-right: 30px;
}

.advantage__title_main {
  font-size: 36px;
  line-height: 43px;
  margin-bottom: 8px;
}

.advantage__body_main {
  font-weight: 400;
  font-size: 24px;
  line-height: 28px;
  color: #FCB500;
}

.advantage__title {
  color: #FFFFFF;
}

.advantage__art {
  margin-bottom: 78px;
}

.advantage__body {
  color: #FCB500
}

.advantage__art_main {
  margin-bottom: 45px;
}

.order {
  text-align: center;
  padding-bottom: 112px;
}

.order__btn {
  margin: auto;
}

.btn {
  display: inline-flex;
  flex-grow: 0;
  flex-shrink: 0;
  justify-content: center;
  align-items: center;
  background: orange;
  cursor: pointer;
  min-height: 56px;
  min-width: 256px;
  border-radius: 7px;
}

</style>

