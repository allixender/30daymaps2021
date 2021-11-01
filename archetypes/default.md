---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "/images/blog/{{ replace .Name "-" "_" | title | lower }}.jpg"
tags: ["maps"]
comments: false
draft: true
---
