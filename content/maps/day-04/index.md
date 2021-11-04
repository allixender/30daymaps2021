---
title: "Day 04 Hexagons"
date: 2021-11-04T20:42:04+02:00
image: "/images/maps/day-04.png"
tags: ["maps", "deckgl", "elevation"]
comments: false
draft: false
---

## H3 Elevation Hexagons in pure JavaScript (DeckGL)


[![](../../images/maps/day-04.png)](../../images/maps/day-04.png)

H3 data was sampled from SRTM over Estonia, and aggregated at resolution 6 in a
OGC API DGGS Prototype app. The data is live-queried at the page rendering.
Another little demo to work with DGGS data.

INTERACTIVE HERE: https://allixender.github.io/30daymaps2021/maps/day-04/h3_hexagon_layer.html

- OGC API DGGS Prototype app: https://github.com/allixender/ogcapi-dggs-webdev-python

- playing around with Deck.gl as basic GeoJSON layer
- https://deck.gl/docs/get-started/using-standalone
- https://deck.gl/docs/api-reference/geo-layers/h3-hexagon-layer
