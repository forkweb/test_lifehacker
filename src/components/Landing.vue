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
          <h2 class="section-content__title-loto">Как устроено «Русское лото»</h2>
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

        <div class="section-content-info">
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

        <div class="section-content-info">
          <div class="section-content__quote">
            Лотерея стала сразу всероссийской, она воспринималась как абсолютное чудо. 
            В 90-е годы наша программа была одной из немногих, где действительно исполнялись мечты.
            <span>Михаил Борисов в <a href="#">интервью</a> для «Дни.ру»</span>
          </div>
        </div>


      </div>
    </div>


    <div class="container section2">

      <div class="section-content">

        <div class="section-content-info">
          <h2 class="section-content__title">Что можно выиграть</h2>
        </div>

        <img class="section-content__text-img" src="@/assets/img/img-sec2.jpg" alt="">

        <div class="section-content-info">
          <div class="section-content__text-gray">
            В первых турах можно выиграть от нескольких тысяч до нескольких миллионов рублей, а также автомобили, загородные дома и путешествия. Все выигрыши можно получить в денежном эквиваленте.
          </div>
          <div class="section-content__text-gray">
            Самый крупный приз — джекпот. Это десятки и даже сотни миллионов рублей, он накапливается от тиража к тиражу. Джекпот можно выиграть, если 15 чисел верхнего или нижнего поля билета совпадут с номерами на первых 15 бочонках, вытянутых ведущим из мешка. Сумма рекордного джекпота в «Русском лото» уже больше 
            900 000 000 рублей.
          </div>
        </div>

      <img class="section-content__text-img" src="@/assets/img/img-sec3.jpg" alt="">

      <div class="section-content-info">
        <div class="section-content__text-gray">
          Призовой фонд формируется из половины стоимости всех проданных билетов. 
          С начала 2019 года общая сумма выигрышей составила свыше 3 миллиардов рублей. Победителями стали около 2 миллионов участников лотереи.
        </div>
      </div>

      </div>

    </div>

    <div class="container section3">
      <div class="section-content">
        <div class="section-content-info">
          <h2 class="section-content__title">Самые крупные выигрыши в «Русском лото»</h2>

          <div class="list-block">

            <div class="list-block__item">
              <img src="@/assets/img/1.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Наталья Власова — 506 000 000 рублей.</div>
                <div class="list-block__item-info__text">
                  1 204-й тираж, трансляция от 5 ноября 2017 года. Деньги пенсионерка решила потратить на покупку жилья, отдых, образование дочери 
                  и благотворительность.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/2.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Наталья Власова — 506 000 000 рублей.</div>
                <div class="list-block__item-info__text">
                  1 264-й тираж, трансляция от 1 января 2019 года. Победители вложились в путешествия, покупку квартиры, помощь родственникам и благотворительность. Часть суммы собираются инвестировать.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/3.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Николай и Оксана Мирошниченко — 500 000 000 рублей.</div>
                <div class="list-block__item-info__text">
                  1 264-й тираж, трансляция от 1 января 2019 года. Полмиллиарда планируют потратить на путешествия, выплату ипотеки, помощь родственникам и благотворительность.
                </div>
              </div>
            </div>

          </div>

          <div class="section-content__text-gray">
            В России все лотереи государственные и регулируются Федеральным законом 
            № 138-ФЗ. Организаторами розыгрышей выступают Министерство спорта РФ 
            и Министерство финансов РФ. Они утверждают условия лотерей и заключают контракты с операторами. Часть денег, вырученных от продажи билетов, идёт 
            на финансирование государственных программ по развитию физической культуры 
            и спорта.
          </div>

        </div>
      </div>
    </div>

    <div class="container section4">

      <div class="section-content">

        <div class="section-content-info">
          <h2 class="section-content__title">Где купить билет</h2>
        </div>
        <img class="section-content__text-img" src="@/assets/img/img-sec4.jpg" alt="">

        <div class="section-content-info">
          <div class="list-block">

            <div class="list-block__item">
              <img src="@/assets/img/1.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">На сайте</div>
                <div class="list-block__item-info__text">
                  <a href="#">Здесь</a> можно найти билеты с любимыми числами и купить разом до 100 штук. А ещё доступна опция заказа пяти билетов, в которых будут все числа от 1 до 90.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/2.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">В мобильном приложении</div>
                <div class="list-block__item-info__text">
                  Удобно покупать билеты с <a href="#">iOS и Android</a>, следить за результатами розыгрышей и смотреть трансляции.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/3.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">В розничных точках продаж</div>
                <div class="list-block__item-info__text">
                  На <a href="#">карте</a> можно найти киоски, лотерейные аппараты и партнёрские магазины: «Почта России», «Связной», «Билайн», «МегаФон», «Ростелеком», Tele2, «Перекрёсток», «Пятёрочка», «Бристоль».
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/44.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Через SMS </div>
                <div class="list-block__item-info__text">
                  Нужно найти на специальной <a href="#">странице</a> идентификационный код лотереи и прислать его SMS-сообщением на номер 9999. Деньги спишутся с баланса мобильного телефона.
                </div>
              </div>
            </div>

          </div>

          <div class="section-content__notice">
            Продажи билетов на воскресный тираж закрываются в субботу в 17:20<br>по московскому времени.
          </div>
        </div>

      </div>

    </div>

    <div class="container section5">

      <div class="section-content">
        <div class="section-content-info">
          <div class="section-content__title">Как играть</div>
        </div>
        <img class="section-content__text-img__game" src="@/assets/img/img-sec5.jpg" alt="">
        <div class="section-content-info">
          <div class="section-content__text-gray">
            «Русское лото» снимается в студии со зрителями и специальной комиссией, которая проверяет количество бочонков в мешке перед розыгрышем и следит, чтобы он был проведён по всем правилам. Комплект бочонков хранится в сейфе. К ним могут прикасаться только ведущие, приглашённый гость и служба безопасности.
          </div>
          <div class="section-content__text-gray">
            Подтасовка результатов исключена: все бочонки одинаковые, с гладкой поверхностью. Если какой-то из них оказывается повреждённым, весь комплект заменяют на аналогичный. Он тоже хранится в сейфе. После окончания съёмок сейф с бочонками и студию опечатывают.
          </div>
          <div class="section-content__text-gray">
            В каждом билете «Русского лото» два поля 9 × 3. В каждой строчке — четыре пустые клетки и пять чисел в диапазоне от 1 до 90. Ведущий «Русского лото» достаёт бочонки из мешка по одному и называет их номера. Задача участника — следить за ходом розыгрыша и зачёркивать в билете числа, изображённые на бочонках. Лотерея проводится в несколько туров.
          </div>
        </div>
      </div>

    </div>


    <div class="container section6">

      <div class="section-content">

        <div class="section-content-info">
          <div class="section-content__title">Туры<br>лотереи</div>
        </div>
        <img class="section-content__text-img__game" src="@/assets/img/img-sec6.jpg" alt="">

        <div class="section-content-info">
          <div class="list-block">

            <div class="list-block__item">
              <img src="@/assets/img/1.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Первый тур</div>
                <div class="list-block__item-info__text">
                  Выигрывают билеты, в которых пять чисел в любой из строк раньше других совпадут с номерами бочонков, вынутых ведущим из мешка. Раньше других — значит раньше, чем в других билетах, участвующих 
                  в тираже.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/2.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Второй тур</div>
                <div class="list-block__item-info__text">
                  Здесь выигрывают те билеты, в которых оказались зачёркнуты все 15 чисел в верхнем или нижнем поле. Если это случилось на пятнадцатом ходу, поздравляем — вы выиграли джекпот.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/3.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Третий и последующие туры</div>
                <div class="list-block__item-info__text">
                  На этих этапах выигрывают билеты, в которых раньше других совпадут все 30 чисел.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/44.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">«Кубышка»</div>
                <div class="list-block__item-info__text">
                  Дополнительный тур, который проводят не всегда. В нём выигрывают билеты, где все невыпавшие в тираже числа оказываются в одном поле — верхнем или нижнем.
                </div>
              </div>
            </div>

          </div>

        </div>

      </div>

    </div>


    <div class="container section7">

      <div class="section-content">

        <div class="section-content-info">
          <div class="section-content__title">Где узнать результаты</div>
        </div>

        <img class="section-content__text-img__game" src="@/assets/img/img-sec7.jpg" alt="">

        <div class="section-content-info">
          <div class="section-content__text-gray">
            Иногда участники лотереи покупают билеты и забывают про них. По иронии именно эти билеты часто оказываются счастливыми, а представители лотереи неделями ищут победителей.
          </div>
          <div class="section-content__text-gray">
            Такой прецедент случился с пенсионеркой Натальей Власовой из посёлка Панино Воронежской области, которая сорвала джекпот и выиграла 506 миллионов рублей. Победительница уже хотела выкинуть залежавшийся на серванте билет из прошлого тиража, но случайно обнаружила, что он выигрышный. Вот что можно сделать, чтобы не попасть в такую ситуацию:
          </div>

          <div class="list-block">

            <div class="list-block__item">
              <img src="@/assets/img/1.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Посмотреть трансляцию</div>
                <div class="list-block__item-info__text">
                  Проверенный способ узнать результат раньше всех и хорошая семейная традиция. Трансляция розыгрышей проходит каждое воскресенье в программе «У нас выигрывают!» на НТВ.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/2.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Проверить числа в архиве тиражей</div>
                <div class="list-block__item-info__text">
                  <a href="#">Найдите</a> номер тиража, указанный на билете, и узнайте, какие бочонки ведущий вынул из мешка. Либо введите номер билета на <a href="#">специальной странице</a> и проверьте, счастливый ли он.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/3.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Получить SMS</div>
                <div class="list-block__item-info__text">
                  Если при покупке билета вы указывали номер телефона, на него придёт сообщение о выигрыше свыше 15 тысяч рублей.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/44.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Проверить результаты в мобильном приложении</div>
                <div class="list-block__item-info__text">
                  Программа для iOS и Android предоставляет архив тиражей и присылает push-уведомления со свежими результатами. Также в приложении можно покупать билеты, изучать программу предстоящих розыгрышей и смотреть трансляции.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/55.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Спросить результаты в точках распространения билетов</div>
                <div class="list-block__item-info__text">
                  На случай, если под рукой ни компьютера, ни телефона, а ждать совсем не хочется.
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/66.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Узнать в газете</div>
                <div class="list-block__item-info__text">
                  Результаты тиражей публикуются по средам в «Аргументах и фактах».
                </div>
              </div>
            </div>

            <div class="list-block__item">
              <img src="@/assets/img/77.png" alt="">
              <div class="list-block__item-info">
                <div class="list-block__item-info__title">Узнать по телефону</div>
                <div class="list-block__item-info__text">
                  Номер круглосуточной горячей линии: 8 (900) 555 00 55.
                </div>
              </div>
            </div>

          </div>

        </div>

      </div>
      
    </div>

    <div class="container section8">

      <div class="section-content">

        <div class="section-content-info">
          <div class="section-content__title">Как получить выигрыш</div>
        </div>

        <img class="section-content__text-img__game" src="@/assets/img/img-sec8.jpg" alt="">

        <div class="section-content-info">
          <div class="section-content__text-gray">
            Чтобы получить выигрыш, нужно предъявить паспорт и лотерейный билет. Забрать приз можно в течение шести месяцев после обращения за выигрышем и подачей заявления.
          </div>
          <div class="section-content__text-gray">
            Если в этот срок получить выигрыш по какой-то причине не удалось, нужно заполнить специальную форму, которая есть на <a href="#">сайте «Столото»</a>, и обратиться в лотерейный центр в Москве. 
          </div>
          <div class="section-content__text-gray">
            В этом случае выигрыш будет ждать победителя ещё три года. Все выигрыши, за которыми никто не пришёл, перечисляются в государственный бюджет.
          </div>
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

