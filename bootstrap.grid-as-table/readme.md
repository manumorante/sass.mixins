### Usage

Use <code>.row-table-xs</code> in <code>.row</code> when you need cols in xsmall version (<code>.col-sx-...</code>)

```scss
.row-table.row-table-xs {
  @include row-table;
}

@media (min-width: $screen-sm) {
  .row-table {
    @include row-table;
  }
}
```

```html
<div class="row row-table row-table-xs">
  <div class="col-xs-6"> ...  </div>
  <div class="col-xs-6"> ... </div>
</div>
```

---
Manu Morante // Created October 17, 2013 // Updated October 8, 2014
