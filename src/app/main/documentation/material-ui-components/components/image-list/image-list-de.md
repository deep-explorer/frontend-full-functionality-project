---
title: Grid List React Komponente
components: ImageList, ImageListItem, ImageListItemBar
---

# Rasterliste (Grid List)

<p class="description">Rasterlisten zeigen eine Sammlung von Bildern in einem organisierten Raster an.</p>

[Rasterlisten](https://material.io/design/components/image-lists.html) repräsentieren eine Sammlung von Elementen in einem sich wiederholenden Muster. Sie verbessern das visuelle Verständnis der Inhalte, die sie enthalten.

## Nur-Bild Raster Liste

Ein einfaches Beispiel für ein scrollbare `RasterList` mit Bildern.

{{"demo": "pages/components/image-list/ImageImageList.js", "hideEditButton": true}}

## Rasterliste mit Titelleisten

In diesem Beispiel wird die Verwendung der `ImageListItemBar` veranschaulicht, um jeweils eine Überlagerung zu jedem `ImageListItem`hinzuzufügen. Die Überlagerung kann einen `title`, `subtitle` und eine sekundäre Aktion aufnehmen - in diesem Beispiel ein `IconButton`.

{{"demo": "pages/components/image-list/TitlebarImageList.js", "hideEditButton": true}}

## Einzeilige Rasterliste

Dieses Beispiel zeigt eine horizontale, durchlaufbare, einzeilige Rasterliste von Bildern. Horizontales Scrollen von Rasterlisten wird empfohlen, da das Scrollen typische Lesemuster stört und das Verständnis beeinträchtigt. Eine Ausnahme ist eine horizontal scrollende, einzeilige Rasterliste von Bildern, z.

{{"demo": "pages/components/image-list/SingleLineImageList.js", "hideEditButton": true}}

## Erweiterte Rasterliste

In diesem Beispiel werden "vorgestellte" Fliesen dargestellt, wobei die Eigenschaften `rows` und `cols` die Größe der Kacheln festlegen und der Abstand durch die `padding` Eigenschaft einstellen wird. Die Kacheln haben eine angepasste Titleleiste, an der Spitze positioniert ist und einem benutzerdefinierten Gradienten `titleBackground` hat. Die sekundäre Aktion `IconButton` befindet sich links.

<<<<<<< HEAD:docs/src/pages/components/grid-list/grid-list-de.md
{{"demo": "pages/components/grid-list/AdvancedGridList.js", "hideEditButton": true, "defaultCodeOpen": false}}
=======
{{"demo": "pages/components/image-list/AdvancedImageList.js", "hideEditButton": true, "defaultCodeOpen": false}}
>>>>>>> [GridList] Rename to ImageList & add deprecation warnings (#22363):docs/src/pages/components/image-list/image-list-de.md
