# Dark Style for Mapbox GL

For use with some implementation of [Mapbox GL](https://www.mapbox.com/mapbox-gl/), such as [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js/).

## Usage

```
var map = new mapboxgl.Map({
  container: 'map', 
  style: 'https://cdn.rawgit.com/friedbunny/mapbox-gl-style-dark/master/dark-v7.json',
  center: [45.56, -122.78],
  zoom: 8
});
```

## Example

[Interactive example with Mapbox GL.](./example/index.html)

This style is meant primarily to be used as a basis for overlays, rather than detailed wayfinding.

![alt text](./example/example.jpg "Usage")

## Label Language

If you'd like to always have English labels (instead of localized), change the `@name` constant to `{name_en}`.
