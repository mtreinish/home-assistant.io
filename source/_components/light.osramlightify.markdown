---
layout: page
title: "Osram Lightify"
description: "Instructions how to integrate Osram Lightify into Home Assistant."
date: 2016-05-29 08:00
sidebar: true
comments: false
sharing: true
footer: true
logo: osramlightify.png
ha_category: Light
---

The `osramlightify` platform allows you to integrate your [Osram Lightify](http://www.osram.com/osram_com/products/led-technology/lightify/index.jsp) into Home Assistant.

```yaml
# Example configuration.yaml entry
light:
  platform: osramlightify
  host: 192.168.0.50
```
Configuration variables:

- **host** (*Required*): IP address of the Osram Lightify bridge, eg. `192.168.1.50`

