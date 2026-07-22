# Countries in the Globe

A Three.js country-typing game on a real-time Earth.

## Imagery and data

- Day surface: NASA Blue Marble.
- Night lights: NASA Black Marble, bundled as `assets/earth-night.jpg`.
- Cloud layer: three.js Earth cloud texture, bundled as `assets/earth-clouds.png`.
- Water/specular map: three-globe example assets.
- Country boundaries: Natural Earth via world-atlas.

The day/night terminator is calculated in the browser from the device's UTC
clock, including seasonal solar declination and the equation of time.
