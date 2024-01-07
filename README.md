```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          -118.2437,
          34.0522
        ]
      },
      "properties": {
        "title": "Los Angeles",
        "color": "7e7e7e"
      },
      "id": 0
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          -0.1276,
          51.5074
        ]
      },
      "properties": {
        "title": "London",
        "description": "Singapore"
      }
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          114.1095,
          22.3964
        ]
      },
      "properties": {
        "title": "Hello"
      },
      "id": 2
    },
    {
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [
          103.8198,
          1.3521
        ]
      },
      "properties": {
        "title": "Hong Kong",
        "marker-color": "#00FFFF"
      },
      "id": 3
    }
  ]
}
```
```topojson
{
  "type": "Topology",
  "objects": {
    "locations": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "coordinates": [-118.2437, 34.0522],
          "properties": {
            "title": "Los Angeles",
            "marker-color": "#FFA500",
            "marker-size": large8",
            "cloud-provider": "AWS"
          }
        },
        {
          "type": "Point",
          "coordinates": [-0.1276, 51.5074],
          "properties": {
            "title": "London",
            "marker-color": "#0000FF",
            "marker-symbol": "circle",
            "marker-size": "large",
            "cloud-provider": "Tencent Cloud"
          }
        },
        {
          "type": "Point",
          "coordinates": [103.8198, 1.3521],
          "properties": {
            "title": "Singapore",
            "marker-color": "#0000FF",
            "marker-size": "large",
            "cloud-provider": "Tencent Cloud"
          }
        }
      ]
    }
  },
  "arcs": [],
  "transform": {
    "scale": [1, 1],
    "translate": [0, 0]
  },
  "bbox": [-118.2437, 1.3521, 103.8198, 51.5074]
}
```
