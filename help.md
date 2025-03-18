# markdown

внутри \`\` -> код, не рендерится

вход

    `код`

результат

`код`

после первого tab -> код

вход

    \tкод
результат

    код


## Заголовки

    # ## ### #### ##### ######

заголовки разных уровней

## шрифт

`*code*` -> *code*

`**code**` -> **code**

`_code_` -> _code_

`__code__` -> __code__

`D<sub>code</sub>` -> D<sub>code</sub>

`D<sup>code</sup>` -> D<sup>code</sup>

## Ссылка

`[текст](ссылка)`

`[шрифт](ссылка на шрифт)` -> [шрифт](#шрифт)

`[dkk](ссылка на dkk)` -> [dkk](https://t.me/dkkru)

## Таблица

    |колонка 1|колонка 2|
    |aliment 1|aliment 2|
    |ячейка a1|ячейка a2|

---

    |col1|col2|
    |:-|:-:|
    |a1|a2|

|column1|column2|
|:-|:-:|
|a1|a2|

## картинка

картинка всегда даётся по ссылке

`![pic1](img\ex1.jpg)` -> ![pic1](img\1a1.png)

`<img align = 'center' src = 'img\1a1.png' />` -> <img align = 'center' src = 'img\1a1.png' />

я пользуюсь 2м вариантом потому что он по центру текста по высоте и больше похоже на wolfram

## список

    - a
    - b
        - c
    - d

- a
- b
    - c
- d

## Пример 1

### Wolfram

![pic1](img\example.png)

### code

    [ImageAdd](#пример-1)[<img align = 'center' src = 'img\1.png' />`, `<img align = 'center' src = 'img\2.png' />`]`

### render

[ImageAdd](#пример-1)`[`<img align = 'center' src = 'img\1.png' />`, `<img align = 'center' src = 'img\2.png' />`]`

### explanation

    [ImageAdd](#пример-1) -> ссылка на пример

    `[`, `, `,`]` -> промежутки кода выделены для красоты

    <img align = 'center' src = 'img\1.png' /> -> рендер картинки

## Пример 2

### Wolfram

![pic1](img\ex2.png)

### code

    |функция|описание|
    |:-|:-|
    |[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image*, *x*]|[добавление](#добавление-указанной-величины-к-каждому-значению-канала) *x* к значению каждого канала *image*|
    |[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image<sub>1</sub>*, *image<sub>2</sub>*]|[сумма](#ex1-101) изображений так, чтобы каждый пиксель полученного изображения являлся соответственно суммой пикселей *image<sub>1</sub>* и *image<sub>2</sub>*|
    |[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image*, *expr<sub>1</sub>*, *expr<sub>2</sub>*, ...]|[добавление](#сложение-нескольких-изображений) каждого *expr<sub>i</sub>* к *image*; *expr<sub>i</sub>* может быть изображением, числом или цветом|

### render

|функция|описание|
|:-|:-|
|[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image*, *x*]|[добавление](#добавление-указанной-величины-к-каждому-значению-канала) *x* к значению каждого канала *image*|
|[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image<sub>1</sub>*, *image<sub>2</sub>*]|[сумма](#ex1-101) изображений так, чтобы каждый пиксель полученного изображения являлся соответственно суммой пикселей *image<sub>1</sub>* и *image<sub>2</sub>*|
|[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image*, *expr<sub>1</sub>*, *expr<sub>2</sub>*, ...]|[добавление](#сложение-нескольких-изображений) каждого *expr<sub>i</sub>* к *image*; *expr<sub>i</sub>* может быть изображением, числом или цветом|

### explanation

#### таблица с уклонением влево:

    |функция|описание|
    |:-|:-|
    |a|b|

|функция|описание|
|:-|:-|
|a|b|

#### [Команда](ссылка на документацию)

    [ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)

[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)

#### аргументы курсивом и индексом

    [*image<sub>1</sub>*, *image<sub>2</sub>*]

#### описание с ссылкой на заголовок в тексте (одна # + заголовок без пробелов) и оформлением текста

[добавление](#добавление-указанной-величины-к-каждому-значению-канала) *x* к значению каждого канала *image*

#### всё вместе в таблице

    |функция|описание|
    |:-|:-|
    |[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image*, *x*]|[добавление](#добавление-указанной-величины-к-каждому-значению-канала) *x* к значению каждого канала *image*|
    |[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image<sub>1</sub>*, *image<sub>2</sub>*]|[сумма](#ex1-101) изображений так, чтобы каждый пиксель полученного изображения являлся соответственно суммой пикселей *image<sub>1</sub>* и *image<sub>2</sub>*|
    |[ImageAdd](https://reference.wolfram.com/language/ref/ImageAdd.html?q=ImageAdd)[*image*, *expr<sub>1</sub>*, *expr<sub>2</sub>*, ...]|[добавление](#сложение-нескольких-изображений) каждого *expr<sub>i</sub>* к *image*; *expr<sub>i</sub>* может быть изображением, числом или цветом|