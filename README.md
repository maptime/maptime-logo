# maptime logo

A JavaScript-powered instarainbow version of the maptime logo.

## example

```html
<canvas id='logo'></canvas>
<script src='maptime-logo.js'></script>
<script>
maptimeLogo('logo', {
    width: window.innerWidth * 2
});
</script>
```

## api

### `maptimeLogo(id: string, options: object)`

* id is the id of a canvas element on your page
* options is an options object. it is optional. options include `width`, for the width.
