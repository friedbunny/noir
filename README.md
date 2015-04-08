# Noir — a Dark Style for Mapbox GL

For use with some implementation of [Mapbox GL](https://www.mapbox.com/mapbox-gl/), such as [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js/) or [Mapbox GL Native](https://github.com/mapbox/mapbox-gl-native/).

This style is meant primarily to be used as a base for overlays, rather than detailed wayfinding.

## Usage

Javascript:

```javascript
var map = new mapboxgl.Map({
  container: 'map', 
  style: 'https://friedbunny.github.io/noir/noir-v7.json',
  center: [45.56, -122.78],
  zoom: 8
});
```

## Examples

- [Interactive example with Mapbox GL](https://friedbunny.github.io/noir/example.html)

- [Rated cycling tracks](http://ride.kulturny.com) from the ongoing [Ride App](http://ride.report) beta

[![alt text](example.jpg "Rides overlayed on Portland, Oregon")](http://ride.kulturny.com)

## Label Language

If you'd like to always have English labels (instead of localized), change the `@name` constant to `{name_en}`.
