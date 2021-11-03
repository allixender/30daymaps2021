---
title: "Day 03 Polygons"
date: 2021-11-03T20:42:04+02:00
image: "/images/maps/day-03.png"
tags: ["maps", "pydeck", "wfs"]
comments: false
draft: false
---

## The Estonian Statistical Grid


[![](../../images/maps/day-03.png)](../../images/maps/day-03.png)

INTERACTIVE HERE: https://allixender.github.io/30daymaps2021/maps/day-03/json_layer.html


- https://metadata.geoportaal.ee/geonetwork/srv/est/catalog.search#/metadata/23e616e7-aad2-47b8-bdc8-60b6f56fdf16
- WFS service:  https://inspire.geoportaal.ee/geoserver/SU_ruutkaart/wfs?service=WFS&version=2.0.0&request=GetFeature&version=2.0.0&outputFormat=application/json&typenames=SU_ruutkaart:SU.StatisticalGridCell&count=10

- loading straight GeoJSON in EPSG supposedly 3035 (but actually 3301), reading with GeoPandas in order to reproject to WGS84, because GeoJSON should be for most wep apps in EPSG:4326 (and officially only WGS84 is allowed)

- playing around with PyDeck / Deck.gl as basic GeoJSON layer
