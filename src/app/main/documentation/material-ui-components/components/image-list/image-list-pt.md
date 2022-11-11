---
title: Componente React para Lista de Grade
components: ImageList, ImageListItem, ImageListItemBar
---

# Lista de Grade

<p class="description">As listas de grade exibem uma coleção de imagens em uma grade de forma organizada.</p>

[Listas de Grade](https://material.io/design/components/image-lists.html) representam uma coleção de itens em um padrão repetido. Elas ajudam a melhorar a compreensão visual do conteúdo que elas contêm.

## Lista de grade com imagens

Um exemplo simples de uma `ImageList` com imagens.

{{"demo": "pages/components/image-list/ImageImageList.js", "hideEditButton": true}}

## Lista de grade com barras de título

Este exemplo demonstra o uso do `ImageListItemBar` para adicionar uma sobreposição a cada `ImageListItem`. A sobreposição pode acomodar um `title`, `subtitle` e ação secundária - neste exemplo utilizamos um `IconButton`.

{{"demo": "pages/components/image-list/TitlebarImageList.js", "hideEditButton": true}}

## Lista de grade em linha única

Este exemplo demonstra uma lista de grade com imagens, em linha unica e rolável horizontalmente. As listas de grade de rolagem horizontal não são recomendadas porque a rolagem interfere nos padrões de leitura típicos, afetando a compreensão. Uma exceção notável para rolagem horizontal, seria uma lista de grade com imagens em linha única, como uma galeria.

{{"demo": "pages/components/image-list/SingleLineImageList.js", "hideEditButton": true}}

## Lista de grade avançada

Este exemplo demonstra blocos "em destaque", usando as propriedades `rows` e `cols` para ajustar o tamanho do bloco, e a propriedade `padding` para ajustar o espaçamento. Os blocos tem uma barra de título customizada, posicionada no topo e com um gradiente personalizado `titleBackground`. A ação secundária `IconButton` está posicionada à esquerda.

<<<<<<< HEAD:docs/src/pages/components/grid-list/grid-list-pt.md
{{"demo": "pages/components/grid-list/AdvancedGridList.js", "hideEditButton": true, "defaultCodeOpen": false}}
=======
{{"demo": "pages/components/image-list/AdvancedImageList.js", "hideEditButton": true, "defaultCodeOpen": false}}
>>>>>>> [GridList] Rename to ImageList & add deprecation warnings (#22363):docs/src/pages/components/image-list/image-list-pt.md
