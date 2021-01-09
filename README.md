`scroll-behavior: smooth` To make the scroll work in a smooth way.
`align-items: center` just works with `display: flex` setted.

Make a gradient text
```css
.selector {
  background-color: #ff8177;
  background-image: linear-gradient(to top, #ff0844 0%, #ffb199 100%);
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
```

Make a list to be side-by-side
```css
.selector {
  display: flex;
  align-items: center;
  list-style: none;
}
```

To make a three bar options just do:
```css
#mobile-menu {
  position: absolute;
  top: 20%;
  right: 5%;
  transform: translate(5%, 20%);
}

.navbar__toggle .bar {
  display: block;
  cursor: pointer;
}
```
on
```html
<div class="navbar__toggle" id="mobile-menu">
  <span class="bar"></span>
  <span class="bar"></span>
  <span class="bar"></span>
</div>
```

Make the text be filled by the behing color/image
```css
selector {
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
```

???
`rem`
