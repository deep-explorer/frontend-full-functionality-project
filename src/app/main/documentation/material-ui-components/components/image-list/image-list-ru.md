---
title: Сеть изображений, компонент React
components: ImageList, ImageListItem, ImageListItemBar
---

# Сеть изображений

<p class="description">Сеть изображений суть коллекция изображений на упорядоченной сетке.</p>

[Сеть изображений](https://material.io/design/components/image-lists.html) являются коллекцией элементов в повторяющемся шаблоне. Они помогают улучшить визуальное восприятие своего содержания.

## Простая сеть изображений

Простой пример прокручиваемой `Сети изображений`.

{{"demo": "pages/components/image-list/ImageImageList.js", "hideEditButton": true}}

## Сеть изображений с заголовками

Этот пример демонстрирует использование `Полосы заголовка сети изображений`, которую следует добавить в каждый `Заголовок сети изображений`. Мы можем указать `заголовок`, `подзаголовок` и дополнительное действие - в этом примере `кнопка-иконка`.

{{"demo": "pages/components/image-list/TitlebarImageList.js", "hideEditButton": true}}

## Сеть изображений в одну строку

Данный пример показывает сеть изображений в одну строку с горизонтальной прокруткой. Сети изображений с горизонтальнйо прокруткой не рекомендуется применять, так как это может вызвать дискомфорт у пользователей, ведь обычно при чтении используется вертикальная прокрутка. Исключением из этого правила являются сети с горизонтальной прокруткой в одну строку, например галерея.

{{"demo": "pages/components/image-list/SingleLineImageList.js", "hideEditButton": true}}

## Более сложный пример

В этом примере демонстрирует «рекомендуемые» листы, в которых используются свойства `rows` и `cols` чтобы отрегулировать размер плитки, и свойство `padding` чтобы отрегулировать поля между плитками. На плитках можно видеть пользовательскую полосу расположенную вверху с даным значением градиента в свойстве `titleBackground`. Дополнительное действие в `Кнопке-иконке` распложенно по левую сторону.

<<<<<<< HEAD:docs/src/pages/components/grid-list/grid-list-ru.md
{{"demo": "pages/components/grid-list/AdvancedGridList.js", "hideEditButton": true, "defaultCodeOpen": false}}
=======
{{"demo": "pages/components/image-list/AdvancedImageList.js", "hideEditButton": true, "defaultCodeOpen": false}}
>>>>>>> [GridList] Rename to ImageList & add deprecation warnings (#22363):docs/src/pages/components/image-list/image-list-ru.md
