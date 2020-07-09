<template>
<div class="landing">

    <div class="header">
      <div class="container">
        <div class="header-nav">
          <div class="header-nav__logo">
            <img src="~@/assets/img/lifehacker-logo.png" alt="">
            <img src="~@/assets/img/rusloto-logo.png" alt="">
          </div>
          <div class="header-nav__social">
            <a href=""><img src="~@/assets/img/facebook.png" alt=""> </a>
            <a href=""><img src="~@/assets/img/twitter.png" alt=""></a>
            <a href=""><img src="~@/assets/img/vk.png" alt=""></a>
          </div>
        </div>

        <img class="header-barrels" src="~@/assets/img/barrels.png" alt="">

      </div>
    </div>

    <div class="container section1">

      <div class="section1-nav">
        <ul>
          <li onclick="animateScrollTo(document.querySelector('.section1'))">Что можно выиграть</li>
          <li>Где купить билет</li>
          <li>Как играть</li>
          <li>Туры лотереи</li>
          <li>Где узнать результаты</li>
          <li>Как получить выигрыш</li>
        </ul>
      </div>

      <div class="section-content">
        <div class="section-content-info">
          <h2 class="section-content__title">Как устроено «Русское лото»</h2>
          <div class="section-content__text">
            Когда недорогой билет обещает миллионный выигрыш, мы ждём подвоха. Но лотерея не чёрный ящик. В подробностях рассказываем, кто следит за соблюдением правил, сколько денег можно выиграть и как их забрать.
          </div>
          <div class="section-content__text-gray">
            «Русское лото» — это всероссийская государственная лотерея, напоминающая народную игру в лото. С момента появления лотереи в XVI веке в Италии правила существенно не изменились: в современном лото тоже не нужно придерживаться стратегий и просчитывать ходы. Прелесть игры в полном доверии случаю, низкой стоимости билета и возможности получить гораздо больше, чем поставлено на кон.

          </div>
          <div class="section-content__text-gray">
            В этом году лотерее исполнится 25 лет. Первый выпуск «Русского лото» состоялся 16 октября 1994 года. Всё это время её бессменно ведёт Михаил Борисов — тот самый жизнерадостный мужчина с седыми усами в жилетке, которого вы видели по телевизору.
          </div>
        </div>
        
        <img class="section-content__text-img" src="~@/assets/img/img-sec1.jpg" alt="">

        <div class="section-content__text-gray">
            Михаил Борисов никогда не был просто харизматичным ведущим. С первого выпуска он выступал настоящим идеологом лотереи и отвечал за концепцию программы. Именно он придумал сделать из игры культурно-развлекательную семейную передачу. В программу приглашали выступать известных и начинающих звёзд, разыгрывали сценки, рассказывали об исторических событиях, связанных с номером тиража. А ещё Михаил Борисов не пропустил ни одного выпуска за 25 лет.
        </div>

        <div class="section-content__text-gray">
          Сейчас в «Русском лото» разыгрывают автомобили, загородные дома, путешествия 
          и крупные денежные призы, но раньше победителям вручалась и бытовая техника: холодильники, телевизоры, утюги и пылесосы.
        </div>

        <div class="section-content__text-gray">
          За последние 8 лет в программе разыграли больше 24 миллиардов рублей, состоялось несколько помолвок, выходили в эфир и участвовали в тиражах космонавты, а Михаил Борисов перетаскал такое количество мешков с бочонками, что, по его словам, мог бы вручную перегородить Енисей или построить ГЭС.
        </div>

      </div>

    </div>

  

  </div>
</template>

<script>
// import $ from "jquery";

export default {
  watch: {
  },
  methods: {
  },
  create(){
    this.animateScrollTo();
  },
  mounted() {
  },
}
</script>


<style lang="scss" type="text/scss">
  // @import "./style/main.scss";
</style>

