---
title: "{{ replace .Name "-" " " | title }}"
description: ""
date: {{ .Date }}
images: ["{{ .Name | urlize }}.jpg"]
categories: ["General","Blog"]
tags: ["featured"]
keywords: ["{{ replace .Name "-" " " | lower }}"]
author: "ÁcidoBase"
---

![{{ replace .Name "-" " " | title }}]({{ .Name | urlize }}.jpg)
{ .img-fluid }
