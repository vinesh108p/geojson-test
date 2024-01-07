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
        "AWS": "Los Angeles",
        "Tencent": "Hong Kong",
        "color": "blue"
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
        "AWS": "London",
        "Tencent": "Singapore"
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
        "AWS": ""
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
        "AWS": "",
        "color": "red"
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
            "name": "Los Angeles",
            "marker-color": "#FFA500",
            "marker-size": "8",
            "cloud-provider": "AWS"
          }
        },
        {
          "type": "Point",
          "coordinates": [-0.1276, 51.5074],
          "properties": {
            "name": "London",
            "marker-color": "#0000FF",
            "marker-symbol": "circle",
            "marker-size": "12",
            "cloud-provider": "Tencent Cloud"
          }
        },
        {
          "type": "Point",
          "coordinates": [103.8198, 1.3521],
          "properties": {
            "name": "Singapore",
            "marker-color": "#0000FF",
            "marker-size": "12",
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
