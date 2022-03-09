## Ground Height

This U-space service can be used to obtain information about the
height.

### Query Ground Height

Gets the ground height at a specific location

```json
{
  "message type": "query ground height",
  "at": [15.659466, 58.410727],
  "EPSG": 4979
}
```

Parameter description:

- **at** *[array<double, double>]*

  The location (lat, lon in degrees) to obtain the ground height

- **EPSG** *[integer]*

  The coordinate system used (default WGS 84)
  Common EPSG codes

  - EPSG:4326 - WGS 84 (geographic 2D)

    latitude/longitude coordinate system based on the Earth's center
    of mass, used by the Global Positioning System among others.

  - EPSG:4979 - WGS 84 (geographic 3D)

    similar to EPSG:4326 but includes height above the ellipsoid.

  - EPSG:3857 - WGS 84 / Pseudo-Mercator (projected)

    Web Mercator projection used for display by many web-based mapping
    tools, including Google Maps and OpenStreetMap.

Response:

```json
{
  "message type": "response",
  "height": 123.45
}
```

- **height** *[double]*

  the ground height at the requested location
