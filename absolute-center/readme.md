Note this mixin rewrites all position properties.

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t-l.png)

#### SCSS
```scss
.box {
  @include absolute();
}
```

CSS
```css
.box {
  position: absolute;
  top: 0;
  left: 0;
  right: inherit;
  bottom: inherit;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t.png)

#### SCSS
```scss
.box {
  @include absolute(0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: inherit;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t-r.png)

#### SCSS
```scss
.box {
  @include absolute(0, 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: inherit;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t-r-b.png)

#### SCSS
```scss
.box {
  @include absolute(0, 0, 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: 0;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/a.png)

#### SCSS
```scss
.box {
  @include absolute(0, 0, 0, 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t.png)

#### SCSS
```scss
.box {
  @include absolute($top: 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: inherit;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/l.png)

#### SCSS
```scss
.box {
  @include absolute($left: 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: inherit;
  left: 0;
  right: inherit;
  bottom: inherit;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/r.png)

#### SCSS
```scss
.box {
  @include absolute($right: 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: inherit;
  left: inherit;
  right: 0;
  bottom: inherit;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/b.png)

#### SCSS
```scss
.box {
  @include absolute($bottom: 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: inherit;
  left: inherit;
  right: inherit;
  bottom: 0;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t-b.png)

#### SCSS
```scss
.box {
  @include absolute(0, $bottom: 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: inherit;
  bottom: 0;
}
```

![](https://raw.githubusercontent.com/manumorante/sass.mixins/master/absolute-center/images/t-r.png)

#### SCSS
```scss
.box {
  @include absolute(0, $right: 0);
}
```

##### CSS
```css
.box {
  position: absolute;
  top: 0;
  left: inherit;
  right: 0;
  bottom: inherit;
}
```
