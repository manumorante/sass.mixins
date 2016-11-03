Note this mixin rewrites all position properties.

```scss
.box {
  @include absolute();
}
```

```css
.box {
  position: absolute;
  top: 0;
  left: 0;
  right: inherit;
  bottom: inherit;
}
```

```scss
.box {
  @include absolute(0);
}
```

```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: inherit;
}
```

```scss
.box {
  @include absolute(0, 0);
}
```

```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: inherit;
}
```

```scss
.box {
  @include absolute(0, 0, 0);
}
```

```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: 0;
}
```

```scss
.box {
  @include absolute(0, 0, 0, 0);
}
```
```css
.box {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
```

```scss
.box {
  @include absolute($top: 0);
}
```
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: inherit;
}
```

```scss
.box {
  @include absolute($left: 0);
}
```
```css
.box {
  position: absolute;
  top: inherit;
  left: 0;
  right: inherit;
  bottom: inherit;
}
```

```scss
.box {
  @include absolute($right: 0);
}
```
```css
.box {
  position: absolute;
  top: inherit;
  left: inherit;
  right: 0;
  bottom: inherit;
}
```

```scss
.box {
  @include absolute($bottom: 0);
}
```
```css
.box {
  position: absolute;
  top: inherit;
  left: inherit;
  right: inherit;
  bottom: 0;
}
```

```scss
.box {
  @include absolute(0, $bottom: 0);
}
```
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: 0;
}
```

```scss
.box {
  @include absolute(0, $right: 0);
}
```
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: inherit;
}
```
