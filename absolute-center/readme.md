```scss
  @include absolute();
  //
  position: absolute;
  top: 0;
  left: 0;
  right: inherit;
  bottom: inherit;
```

```scss  
  @include absolute(0);
  //
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: inherit;
```

```scss
  @include absolute(0, 0);
  //
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: inherit;
```

```scss
  @include absolute(0, 0, 0);
  //
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: 0;
```

```scss
  @include absolute(0, 0, 0, 0);
  //
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
```

```scss
  @include absolute($top: 0);
  //
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: inherit;
```

```scss
  @include absolute($left: 0);
  //
  position: absolute;
  top: inherit;
  left: 0;
  right: inherit;
  bottom: inherit;
```

```scss
  @include absolute($right: 0);
  //
  position: absolute;
  top: inherit;
  left: inherit;
  right: 0;
  bottom: inherit;
```

```scss
  @include absolute($bottom: 0);
  //
  position: absolute;
  top: inherit;
  left: inherit;
  right: inherit;
  bottom: 0;
```

```scss
  @include absolute(0, $bottom: 0);
  //
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: 0;
```

```scss
  @include absolute(0, $right: 0);
  //
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: inherit;
```
