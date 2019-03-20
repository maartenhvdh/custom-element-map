# Geolocation element

This KC custom element allows you to put a marker on a map and it automatically gets converted to latitude and longitude geo locations.

You can test it by configuring https://amend.cz/geolocation/Geolocation-Leaflet.html url for your custom element.

![screenshot](https://amend.cz/geolocation/geolocation.png)

You can specify the Parameters {JSON} part of the configuration to configure the default width/height of the map, default latitude and longitude and the zoom of the map.
You can configure only some or even none of the parameters:

```
{
    "width": 800,
    "height": 600,
    "lat": 46.123,
    "lng": 16.123,
    "zoom": 10
}
```
