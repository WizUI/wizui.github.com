---
layout: page
title: The Wizardry JavaScript library for User Interface
tagline: The Wizardry JavaScript library for User Interface
---
{% include JB/setup %}

## Motivation for WizUI

**WizUI**, or **WUI**, is a _virtual DOM_ implementation for high performance.

Here at [Wizcorp], we make single-page applications mostly on portable devices that often have many lines of generated HTML.
We need to need to provide a smooth experience for our end users therefore through multiple iteration we created **WizUI**.

**WizUI** allows the programmer to create HTML elements while minimizing interaction with the DOM, and maintain fine-level control over exactly when, where and in what manner data is displayed and how events are handled.

**WizUI** also allows integrate [Tomes], another [Wizcorp] API, to allow easy data binding,
which allows DOM elements to be updated whenever the underlying data associated with it will change.
Very useful for such things as validation, social events, real-time data display and for asynchronous processing.
By fully leveraging the non-blocking nature of Node.js, **WizUI** will perform nearly real-time updating of data and allow the programmer to avoid DOM calls, have more compact code and allow for more reusable user interface components.


## What WuiDom is

[WuiDom] is the base object of the **WizUI** system. It represents the smallest unit of programmatic logic, an object corresponding to an underlying HTML element and that associated data (including, but not limited to, a Tome), events and other properties. WuiDom allows the programmer to keep a reference to generated elements (if desired) or to create throw-away elements. A simple function can create a generic UI template or create a custom view. Because WuiDom inherits from EventEmitter, programmer-defined events can be conditionally emitted and handled by WizUI or other modules.


## WizUI Components

One of the major goals of **WizUI**, aside from reducing interaction with the DOM, is to enable developers to create re-usable user interface components, common behaviours and reusable views. When creating WizUI components, please try to keep that goal in mind. The ideal WizUI component can be used on many views and ideally that means to not making too many assumptions about the underlying data or the the business logic of the game.

Below is a partial list of the existing WizUI components, and what their primary functions are:

### WuiButton

[WuiButton] is one of the basic implementation of a element using WizUI.

### WuiView

[WuiView] is ideal to show different content for a single-page-application (SPA).


[Wizcorp]: http://www.wizcorp.jp "Wizcorp"
[Tomes]: https://github.com/Wizcorp/node-tomes/blob/master/README.md "Tomes"
[WuiDom]: https://github.com/wizUI/WuiDom
[WuiButton]: https://github.com/wizUI/WuiButton
[WuiView]: https://github.com/wizUI/WuiView