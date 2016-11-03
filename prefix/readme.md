### Usage

```scss
.borders {
  @include prefix(border-radius, 10px);
}
```

### Output

```css
.borders {
  -webkit-border-radius: 10px;
     -moz-border-radius: 10px;
      -ms-border-radius: 10px;
          border-radius: 10px;
}
```
