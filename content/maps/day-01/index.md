---
title: "Day 01 Points"
date: 2021-11-01T22:42:04+02:00
image: "/images/maps/day-01.png"
tags: ["maps", "datashader", "wfs"]
comments: false
draft: false
---

## Placenames in Estonia


[![](../../images/maps/day-01.png)](../../images/maps/day-01.png)


- https://metadata.geoportaal.ee/geonetwork/srv/eng/catalog.search#/home
- https://metadata.geoportaal.ee/geonetwork/srv/eng/catalog.search#/metadata/siseministeerium_knr
- a WFS from the Estonian Geoportal: https://inspire.geoportaal.ee/geoserver/GN_kohanimed/wfs
- the OWSlib from OSGeo GeoPython: https://geopython.github.io/OWSLib/usage.html#wfs
- loading all the 371237 points in the service
- aggregating with DataShader: https://datashader.org/
- styling based on the DataShader US Census example: https://examples.pyviz.org/census/census.html
- Higher density of placenames becoming visible
