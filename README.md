# L.Control.CartographicScale

Show the cartographic scale on your Leaflet map.

https://github.com/GreenInfo-Network/L.Control.CartographicScale

http://greeninfo-network.github.io/L.Control.CartographicScale

```
    new L.Control.CartographicScale({
        text: 'Map scale'
    }).addTo(MAP);
```

Or

```
    L.cartographicScaleControl({
        text: 'Map scale'
    }).addTo(MAP);
```


# Options

* **text** -- Text to show before the scale readout, e.g. "Map scale:"


# About Accuracy and Cartographic Scale

Over the last several years, numerous articles have been written about the inaccuracy of trying to convert browser-based maps into cartographic scales. The issue is complex, depending on the projection being used (a "degree" isn't the same square area at the equator as at the poles) and the screen (devices vary in their pixel resolution).

As such, the readout given by this control should be considered **an approximation** and should not be taken seriously for surveying, legal purposes, etc.
