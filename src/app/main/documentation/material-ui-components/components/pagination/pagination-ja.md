---
title: React Pagination component
components: Pagination, PaginationItem
---

# Pagination

<p class="description">Pagination コンポーネントにより、範囲から特定のページを選択できます。</p>

## Basic pagination

{{"demo": "pages/components/pagination/BasicPagination.js"}}

## Outlined pagination

{{"demo": "pages/components/pagination/PaginationOutlined.js"}}

## Rounded pagination

{{"demo": "pages/components/pagination/PaginationRounded.js"}}

## Pagination size

{{"demo": "pages/components/pagination/PaginationSize.js"}}

## Button

必要に応じて、最初のページと最後のページへのボタンを有効にしたり、前のページと次のページへのボタンを無効にしたりできます。

{{"demo": "pages/components/pagination/PaginationButtons.js"}}

## ページネーションの範囲

You can specify how many digits to display either side of current page with the `siblingRange` prop, and adjacent to the start and end page number with the `boundaryRange` prop.

{{"demo": "pages/components/pagination/PaginationRanges.js"}}

## Controlled pagination

{{"demo": "pages/components/pagination/PaginationControlled.js"}}

## Router integration

{{"demo": "pages/components/pagination/PaginationLink.js"}}

## `usePagination`

高度なカスタマイズのユースケースでは、ヘッドレスな`usePagination()` フックを公開しています。 It accepts almost the same options as the Pagination component minus all the props related to the rendering of JSX. The Pagination component uses this hook internally.

```jsx
import { usePagination } from '@material-ui/lab/Pagination';
```

{{"demo": "pages/components/pagination/UsePagination.js"}}

## Table pagination

`Pagination` コンポーネントは、無限ローディングが使用されない場合に任意のアイテムのリストをページネーションするように設計されています。 It's preferred in contexts where SEO is important, for instance, a blog.

For the pagination of a large set of tabular data, you should use the `TablePagination` component.

{{"demo": "pages/components/pagination/TablePagination.js"}}

You can learn more about this use case in the [table section](/components/tables/#custom-pagination-options) of the documentation.

## アクセシビリティ

### ARIA

The root node has a role of "navigation" and aria-label "pagination navigation" by default. The page items have an aria-label that identifies the purpose of the item ("go to first page", "go to previous page", "go to page 1" etc.). You can override these using the `getItemAriaLabel` prop.

### Keyboard

The pagination items are in tab order, with a tabindex of "0".
