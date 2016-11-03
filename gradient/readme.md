### Usage

```scss
  .box {
    @include gradient(#000, #FFF);
  }
```

Output

```css
.box {
  background: #000;
  background: -moz-linear-gradient(top, #000 0%, #FFF 100%);
  background: -webkit-linear-gradient(top, #000 0%, #FFF 100%);
  background: linear-gradient(to bottom, #000 0%, #FFF 100%);
}
```
