# Dark Style for Mapbox GL

For use with some implementation of [Mapbox GL](https://www.mapbox.com/mapbox-gl/), such as [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js/).

This style is meant primarily to be used as a base for overlays, rather than detailed wayfinding.

## Usage

Javascript:

```javascript
var map = new mapboxgl.Map({
  container: 'map', 
  style: 'https://friedbunny.github.io/mapbox-gl-style-dark/dark-v7.json',
  center: [45.56, -122.78],
  zoom: 8
});
```

iOS:

```objective-c
- (void)viewDidLoad {
  // remember to do init like access token, etc

  NSString *styleJsonPath = [[NSBundle mainBundle] pathForResource:@"styles/dark-v7" ofType:@"json"];
  NSString *styleJson = [NSString stringWithContentsOfFile:styleJsonPath encoding:NSUTF8StringEncoding error:NULL];
    
  self.mapView = [[MGLMapView alloc] initWithFrame:self.view.bounds styleJSON:styleJson accessToken:accessToken];

  // ... and the rest of your setup
}
```

## Examples

- [Interactive example with Mapbox GL](https://friedbunny.github.io/mapbox-gl-style-dark/example.html)

- [Rated cycling tracks](http://ride.kulturny.com) from the ongoing [Ride App](http://ride.report) beta

[![alt text](example.jpg "Rides overlayed on Portland, Oregon")](http://ride.kulturny.com)

## Label Language

If you'd like to always have English labels (instead of localized), change the `@name` constant to `{name_en}`.
