---
layout: page
title: "WuiDom"
description: ""
group: WizComponent
weight: 1
---
{% include JB/setup %}

## What is WuiDom

[WuiDom] is the base object of the WizUI system. It represents the smallest unit of programmatic logic,
an object corresponding to an underlying HTML element and that associated data (including, but not
limited to, a Tome), events and other properties. WuiDom allows the programmer to keep a reference
to generated elements (if desired) or to create throw-away elements. A simple function can create a
generic UI template or create a custom view. Because WuiDom inherits from EventEmitter,
programmer-defined events can be conditionally emitted and handled by WizUI or other modules.

## API
See [WuiDom] GitHub page

[WuiDom]: https://github.com/WizUI/WuiDom