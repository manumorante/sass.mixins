### Usage

```scss
body {
  @include text-smoothing;
}
```

### Output

```css
body,
body *,
body *::after,
body *::before {
  text-rendering: optimizeLegibility;
  -webkit-text-stroke: 0;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```

---
Manu Morante // Created February 3, 2015
