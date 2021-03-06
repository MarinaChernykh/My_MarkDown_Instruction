# Язык Markdown: инструкция

## Заголовки
В языке Markdown предусмотрены заголовки разных уровней. Для того, чтобы текст стал заголовком, необходимо поставить перед ним (в начале строки) 1 или несколько знаков # и пробел после них. В зависимости от того, сколько символов # проставлено, такого уровня будет заголовок (где 1 уровень - самый крупный текст, а 6 - самый мелкий)

Примеры:
# Заголовок 1
## Заголовок 2
### Заголовок 3
#### Заголовок 4
##### Заголовок 5
###### Заголовок 6
----


## Курсив
Для курсивного написания текста нужно обрамить его * или _

Например:

*Курсивный шрифт*

_И это тоже курсивный шрифт_

## Полужирный
Для полужирного написания текста нужно обрамить его ** или __

Например:

**Полужирный шрифт**

__И это тоже полужирный шрифт__

## Курсивный полужирный
Два шрифта выше можно совместить: для этого нужно использовать комбинацию * и _:

Для полужирного написания текста нужно обрамить его ** или __

Например:

_**Курсивный полужирный шрифт**_

__*И это тоже курсивный полужирный шрифт*__


## Списки
### Нумерованные списки
Для создания нумерованного списка нужно в начале строки поставить номер пункта (цифру от 1 и далее), точку и пробел:
1. Важный пункт 1
2. Важный пункт 2
3. Важный пункт 3
### Ненумерованные списки
Для создания ненумерованного списка (списка с буллитами) в начале строки нужно поставить звездочку (*), плюс (+) или тире (-) и пробел:
* Важный пункт 1
* Важный пункт 2
+ Важный пункт А
+ Важный пункт Б
- Важный пункт *
- Важный пункт **

Используя Tab можно создать вложенные списки:
* Важный пункт 1
    * Менее важный пункт 1.1
    * Менее важный пункт 1.2
* Важный пункт 2

## Ссылки
Markdown поддерживает два стиля оформления ссылок:

* Гиперссылка, с немедленным указанием адреса (внутритекстовая)
* Гиперссылка, подобная сноске

Чтобы ссылка была скрыта под текстом, нужно в квадратные скобки поставить отображаемый текст, а саму ссылку поставить в круглые скобки сразу после квадратных (без пробела). Также в круглых скобках можно в кавычках написать всплывающую подсказку).

[Geek Brains](https://gb.ru/)

[Geek Brains](https://gb.ru/ "Тут я учусь")

Если ссылку не надо скрывать под текстом, ее надо заключить в треугольные скобки <>. Но это не точно.

<https://gb.ru/>

## Цитаты
Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также можно делать вложенные цитаты (цитаты внутри цитат). Для их разметки нужно поставить 2 и более знаков «>».Уровень цитирования не может превышать 15-й.

>Здесь могла бы быть цитата умного человека
>>Но ее нет

## Изображения
Чтобы вставить в текст изображение, достаточно написать следующее:
![Текст, который будет показан, если изображение не загрузится](имя файла)
![Привет, это котик](cat.jpg)
При этом нужно добавить файл .gitignore и указать в нем имя файла с изображениям - так система будет игнорировать файл с рисунком при коммитах.

## Горизонтальные разделительные линии
Чтобы создать горизонтальную линию, нужно поставить 3 (или более)дефиса (-) или звездочки (*) на отдельной строке.

---

## THE END