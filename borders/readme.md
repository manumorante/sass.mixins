Usasge

```scss
.all    { @include borders($borders: all) }
.top    { @include borders($borders: top) }
.right  { @include borders($borders: right) }
.bottom { @include borders($borders: bottom) }
.left   { @include borders($borders: left) }
.sides  { @include borders($borders: left right) }
```

Output
```scss
.all {
  border: #000 1px solid;
}

.top {
  border-top-color: #000;
  border-top-width: 1px;
  border-top-style: solid;
}

.right {
  border-right-color: #000;
  border-right-width: 1px;
  border-right-style: solid;
}

.bottom {
  border-bottom-color: #000;
  border-bottom-width: 1px;
  border-bottom-style: solid;
}

.left {
  border-left-color: #000;
  border-left-width: 1px;
  border-left-style: solid;
}

.sides {
  border-left-color: #000;
  border-left-width: 1px;
  border-left-style: solid;
  border-right-color: #000;
  border-right-width: 1px;
  border-right-style: solid;
}
```
