#### Usage

```scss
.borders {
  @include prefix(border-radius, 10px);
}
```

Output

```css
.borders {
  -webkit-border-radius: $value;
  -moz-#{$prop}: $value;
  -ms-#{$prop}: $value;
  #{$prop}: $value;
}
```
