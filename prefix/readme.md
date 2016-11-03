### Usage

#### Using defautls prefixes

```scss
.borders {
  @include prefix(border-radius, 10px);
}
```

Output

```css
.borders {
  -webkit-border-radius: 10px;
     -moz-border-radius: 10px;
      -ms-border-radius: 10px;
          border-radius: 10px;
}
```

#### Using custom prefixes

```scss
.borders {
  @include prefix(border-radius, 10px, moz);
}
```

Output

```css
.borders {
  -moz-border-radius: 10px;
       border-radius: 10px;
}
```
