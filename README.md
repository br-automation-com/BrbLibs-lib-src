# BrbLibs
BrbLib (general functions), BrbVc4 (functions for VC4), BrbVc2d (functions to draw dynamical 2d models for VC4)

## Table of Contents
* [Introduction BrbLib](#Introduction_BrbLib)
* [Introduction BrbLibVc4](#Introduction_BrbLibVc4)
* [Introduction BrbLibVc2d](#Introduction_BrbLibVc2d)

<a name="Introduction_BrbLib"></a>
## Introduction BrbLib
Many useful functions/function blocks to solve general requirements at programming a B&R plc. Everything is well documented, but only in german. Excerpt of functionality:
  * String and unicode string handling (conversion Hex&Bin, Cut, Insert, Trim, Pad, Split, Swap, ToLower, ToUpper, etc...)
  * Time formats (Conversion to/from Text, calulation, determine weekday, etc...)
  * Files (loading and saving variables to binary/text file)
  * Memory management (Array-Management, Bit functions, etc...)
  * Step sequencers (logging, timeout handling, stop watch, etc...)
  * USB support (determine usb sticks on plug in and out with automatic linking)
  * Random values (generating random values for various datatypes)
  * Scaling (handling of analog in/outputs)
  * Timer-Switch for 1 channel (switching on many settings like date, weekday etc.)

[**For a detailed description see this link**](https://github.com/br-automation-com/BrbLibs-lib-src/blob/main/BrbLib%20-%20Dokumentation.pdf)

<a name="Introduction_BrbLibVc4"></a>
## Introduction BrbLibVc4
Many useful functions/function blocks for a transparent and intuitive coding of a Visual Components 4 logic. Everything is well documented, but only in german. Excerpt of functionality:
  * Read out touch state
  * Mighty page navigation handling (back to previous page, init and exit functionality, parameterizable screen saver, etc...)
  * Support of all native controls with structures and functions (Button, Bargraph, Drawbox, Dropdown, etc...)
  * Implementation of none native controls (Check box, option box, incremental button, jog button, scroll bars, tab control, touchgrid, etc...)
  * Support of owner drawing (dashed forms, clipping, coordinate correction, etc...)
  * Trend control with a lots of features (1µs resolution, touch usability for scrolling/zooming/cursors, various source settings, easy visual extension with callbacks, etc...)
  * X/Y-Plot control with a lots of features (touch usability for scrolling/zooming/cursor, various source settings, easy visual extension with callbacks, etc...)
  * Treeview control with a lots of features (touch usability for expanding/scrolling, icon support, easy visual extension with callbacks, etc...)

[**For a detailed description see this link**](https://github.com/br-automation-com/BrbLibs-lib-src/blob/main/BrbLibVc4%20-%20Dokumentation.pdf)

<a name="Introduction_BrbLibVc2d"></a>
## Introduction BrbLibVc2d
Functions for drawing a dynamical 2d model under VC4. Everything is well documented, but only in german. Excerpt of functionality:
  * Building a model with primitive elements (point, line, triangle, tetragon, circle and ellipse)
  * Animating of elements or models with transformation (scaling, translation and rotating)
  * Transformation with 2 alternative concepts (sequential and matrix)
  * Easy visual extension with callbacks

[**For a detailed description see this link**](https://github.com/br-automation-com/BrbLibs-lib-src/blob/main/BrbLibVc2d%20-%20Dokumentation.pdf)

