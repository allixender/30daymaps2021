---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
publishdate: {{ .Date }}
image: "/images/maps/{{ title | lower }}.png"
tags: ["maps"]
comments: false
draft: true
---
