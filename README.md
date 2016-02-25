# Noir — a Dark Style for Mapbox GL

**Warning: This style is rather out of date! Use [Mapbox Dark](https://www.mapbox.com/blog/mapbox-light-and-dark-for-gl/) instead.**

For use with libraries that implement the [Mapbox GL Style Spec](https://www.mapbox.com/mapbox-gl-style-spec/), such as [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js/) or [Mapbox GL Native](https://github.com/mapbox/mapbox-gl-native/).

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

- [Rated cycling tracks](http://ride.kulturny.com) from the [Ride App](http://ride.report) beta

[![alt text](example.jpg "Rides overlaid on Portland, Oregon")](http://ride.kulturny.com)

## Label Language

If you'd like to always have English labels (instead of localized), change the `@name` constant to `{name_en}`.
