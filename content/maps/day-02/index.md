---
title: "Day 02 Lines"
date: 2021-11-02T22:42:04+02:00
image: "/images/maps/day-02.png"
tags: ["maps", "pydeck", "wfs"]
comments: false
draft: false
---

## Tartu Roads


[![](../../images/maps/day-02.png)](../../images/maps/day-02.png)

INTERACTIVE HERE: https://allixender.github.io/30daymaps2021/maps/day-02/path_layer.html


- https://avaandmed.eesti.ee/datasets/teeregister
- WFS service:  https://teeregister-api.mnt.ee/teenus/wfs?request=GetCapabilities&service=WFS
- the OWSlib from OSGeo GeoPython: https://geopython.github.io/OWSLib/usage.html#wfs
- loading Tartu bbox roads as GML in EPSG 3301, reading with GeoPandas
- COORDINATE AXIS SWITCH ... lot's of cleaning up
- playing around with PyDeck / Deck.gl


I also looked at https://metadata.geoportaal.ee/geonetwork/srv/est/catalog.search#/metadata/%7B002F8C73-BF14-4F6D-9D4D-56765FDB5E94%7D but couldn't get the data export to work properly:

https://inspire.maaamet.ee/arcgis/rest/services/public/tn_rrc/MapServer/exts/InspireFeatureDownload/service?request=GetCapabilities&service=WFS
