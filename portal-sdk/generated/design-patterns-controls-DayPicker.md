﻿# DayPicker

 
<a name="basics"></a>
### Basics
The DayPicker component enables a user to pick a day.



<!-- TODO get an IMAGE to embed here -->

<a name="interact-with-the-control-and-get-sample-source-code"></a>
### Interact with the control and get sample source code
To see the latest control, change options and get source code for your project, click here.

<a href="https://ms.portal.azure.com/?Microsoft_Azure_Playground=true#blade/Microsoft_Azure_Playground/ControlsIndexBlade/DayPickerPlayground" target="_blank">DayPicker in the interactive controls playground</a>

Learn more about the controls playground [./top-extensions-controls-playground.md](./top-extensions-controls-playground.md)


<!-- TODO get an SAMPLE CODE to embed here -->

 
<a name="when-to-use"></a>
### When to use
Use the DayPicker when the user must select a day.

There are a set of date, time and duration pickers available in the SDK.  Choose the one that is most suitable to your need.
* DatePicker
* DateTimePicker
* DateTimeRangePicker
* DayPicker
* DurationPicker
* TimePicker



 
<a name="design-best-practices"></a>
### Design best practices

<a name="design-best-practices-figma-design-toolkit"></a>
#### Figma design toolkit

<a name="design-best-practices-do"></a>
#### Do

* Use the control as a single entity.
* Set the default date to the current date unless a specific date is required for context (e.g. the date of the conference).
* The control is designed to resize relative to available screen width. Allow it to render in either wide or narrow as appropriate.
* The control renders date in a specific format. If allowing for manual entry of date, provide helper text in the appropriate format.

<a name="design-best-practices-don-t"></a>
#### Don&#39;t

* Don't attempt to break apart year from month/day selectors. If granularity is required, use the Dropdown control or something similar.
* Don't attempt to force resize the control in any way.
* Don't force the control to render one mode vs. the other (year or month/day)



 
<a name="developer-tips-and-tricks"></a>
### Developer tips and tricks



 
<a name="related-docs"></a>
### Related docs

For overall Azure design guidance see http://aka.ms/portalfx/design

