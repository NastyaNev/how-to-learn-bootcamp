# **How to learn**

## *Сайт, рассказывающий о сложностях и методиках обучения.*

Ссылка на демо :point_right: [здесь](https://how-to-learn-from-nastyanev.surge.sh/ "Ссылка опубликованного проекта на surge.sh")

Самостоятельное обучение часто бывает ~~невозможным~~ очень сложным. Сайт **How to learn** рассказывает о методиках и лайфхаках в обучении.

На первой стадии проекта были сделаны разделы:
  * Шапка сайта *header* с ссылкой на современные методики обучения.
  * Раздел *content*, где в формате таблицы были рассмотрены главные проблемы в обучении.
  * Секция *feynman*, презентующая метод обучения американского физика Ричарда Фейнмана. Об этом неординарном человеке можно подробнее почитать в [Википедии](https://ru.wikipedia.org/wiki/%D0%A4%D0%B5%D0%B9%D0%BD%D0%BC%D0%B0%D0%BD,_%D0%A0%D0%B8%D1%87%D0%B0%D1%80%D0%B4 "Ссылка на статью в Википедии").
  * Также был составлен раздел *digits* с различными цифрами и фактами об обучении. А вы знали, что объем памяти человеческого мозга _1000 терабайт_?
  * Раздел *kaufman* с принципами обучения от Джорджа Кауфмана.
  * ~~Подвал~~ Завершающий раздел сайта *footer*.

На второй стадии проекта было добавлено 5 новых разделов:
  1. *techniques* с техниками обучения от Барбары Оакли.
  2. *video* с парочкой видео для тех, кто любит прокрастинировать.
  3. *oakley* с историей Барбары Оакли.
  4. *khan* с ссылкой на уникальную книгу Салама Хана.
  5. *resources* с ссылками на другие полезные ресурсы по теме.

Также во второй части была реализована анимация на некоторые детали сайта через кейфреймы:
```css
@keyframes rotation {
    from  {
      transform: rotate(0deg);
    }
     
    to  {
      transform: rotate(360deg);
    }
  }
```

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

**Код организован** согласно БЭМ методологии.

**В планах**:

- сделать код кроссбраузерным
- сделать адаптивную верстку. 
