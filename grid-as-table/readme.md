### Usage

Use '.row-table-xs' in '.row' when you need cols in xsmall version (.col-sx-...)

```scss
.row-table.row-table-xs {
  @include row-table;
}

@media (min-width: $screen-sm) {
  .row-table {
    @include row-table;
  }
};
```

```html
<div class="row row-table row-table-xs">
  <div class="col-xs-6"> ...  </div>
  <div class="col-xs-6"> ... </div>
</div>
```
