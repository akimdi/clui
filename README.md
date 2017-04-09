# CLUI ![](https://travis-ci.org/VladimirMarkelov/clui.svg)
Command Line User Interface (Console UI inspired by TurboVision) with built-in theme support. Please see screenshots of working examples at the end of the README.

## Current version
The current version is 0.5.0 and it has a lot of breaking changes comparing to previous one. Please see details in [changelog](./changelog).

## Documentation
* ![Introduction](/docs/intro.md)
* ![Getting started](/docs/hello.md)
* ![Layout manager](/docs/layout.md)
* ![Basic standrd control methods and properties](/docs/widget.md)
* ![About Windows](/docs/window.md)

## The list of available controls
* Window (Main control container - with maximize, window order and other window features)
* Label (Horizontal and Vertical with basic color control tags)
* Button (Simple push button control)
* EditField (One line text edit control with basic clipboard control)
* ListBox (string list control with vertical scroll)
* TextView (ListBox-alike control with vertical and horizontal scroll, and wordwrap mode)
* ProgressBar (Vertical and horizontal. The latter one supports custom text over control)
* Frame (A decorative control that can be a container for other controls as well)
* CheckBox (Simple check box)
* Radio (Simple radio button. Useless alone - should be used along with RadioGroup)
* RadioGroup (Non-visual control to manage a group of a few RadioButtons)
* ConfirmationDialog (modal View to ask a user confirmation, button titles are custom)
* SelectDialog (modal View to ask a user to select an item from the list - list can be ListBox or RadioGroup)
* BarChart (Horizontal bar chart without scroll)
* SparkChart (Show tabular data as a bar graph)
* GridView (Table to show structured data - only virtual and readonly mode with scroll support)

## Screenshots
The main demo (theme changing and radio group control)

<img src="./demos/clui_demo_main.gif" alt="Main Demo">

The screencast of demo:

<img src="./demos/demo.gif" alt="Library Demo">

The library is in the very beginning but it can be used to create working utilities: below is the example of my Dilbert comix downloader:

<img src="./demos/dilbert_demo.gif" alt="Dilbert Downloader">
