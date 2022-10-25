# 300 - Buidling Our Application

## 100 - A map with hardly any visible layers

In Maputnik, hide all layers (except for the text) as follows:

![Screenshot 2022-10-25 122646](https://user-images.githubusercontent.com/1499433/197750832-41c1a836-325c-4171-a893-bddf5486ddc1.png)

Now export the JSON:

```
{
  "id": "road_one_way_arrow_opposite",
  "type": "symbol",
  "source": "openmaptiles",
  "source-layer": "transportation",
  "minzoom": 15,
  "filter": ["==", "oneway", -1],
  "layout": {
    "icon-image": "arrow",
    "symbol-placement": "line",
    "icon-rotate": 180,
    "visibility": "none"
  }
}
```
Map

```
{
  "id": "road_one_way_arrow_opposite",
  "type": "symbol",
  "source": "openmaptiles",
  "source-layer": "transportation",
  "minzoom": 15,
  "filter": ["==", "oneway", -1],
  "layout": {
    "icon-image": "arrow",
    "symbol-placement": "line",
    "icon-rotate": 180,
    "visibility": "none"
  },
  "paint": {
    "icon-translate-anchor": "viewport"
  }
}
```
Viewport
