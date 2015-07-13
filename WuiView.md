---
layout: page
title: "WuiView"
description: ""
group: WizComponent
weight: 5
---
{% include JB/setup %}
## What is WuiView

This component has a really simple API, allows for the created, opening, opened, closing and
closed events. On each of these events, the game programmer can perform logic related to loading
data, binding other events, animation or other game events. Inherits from [WuiDom].

## Using the WuiView component

A [WizView] often contains other WuiDom and WizUI elements, and is usually a container element, used
for display, hide and show logic.
It can interact with [NavTree] to enable smooth navigation on a single page  applications.

## API
See [WuiView] GitHub page

[WuiDom]: https://github.com/WizUI/WuiDom "WuiDom"
[WuiView]: https://github.com/WizUI/WuiView "WuiView"
[NavTree]: https://github.com/Wizcorp/NavTree "NavTree"