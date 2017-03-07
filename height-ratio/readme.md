### Usage

```scss
$image-width: 200px;
.image {
  width: $image-width;
  @include height-ratio($image-width, 4 3);
}
```

### Output

```css
.image {
  width: 200px;
  height: 150px;
}
```

---
Manu Morante // Created November 18, 2014
