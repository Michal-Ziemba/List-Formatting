# Color Picker Format

## Summary

This sample pre defined palettes of colors by Microsoft documentation [color enumeration in Power Apps](https://docs.microsoft.com/en-us/powerapps/maker/canvas-apps/functions/function-colors) that can be used in solutions as color picker. It's also include 2 additional colors palettes such us **"12 sections"** and **"Basic"** that can be used as color picker.

![color picker format](./assets/ColorPickerOptions.gif)

## color-picker-all-format

This format allow users to select up to 140 colors existing in Power Apps, it's also possible to select what colors can be displayed using field  **ColorF** as filter and include the names of the colors. Sample **"red,azure,gold"**.

If field **ColorF** empty then all 140 colors are displayed. 

![color picker format](./assets/ColorPickerFilter.PNG)

## View requirements
- The format expect the following fields:

Field |Type
--------|---------
Title | Single line of text 
ColorP | Single lines of text
ColorF | Single lines of text

## Sample

Solution|Author(s)
--------|---------
color-picker-all-format.json | [André Lage](https://twitter.com/aaclage)
color-picker-12Sections-format.json | [André Lage](https://twitter.com/aaclage)
color-picker-basic-format.json | [André Lage](https://twitter.com/aaclage)

## Version history

Version|Date|Comments
-------|----|--------
1.0|January 17, 2022|Initial release

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Additional notes
None

<img src="https://pnptelemetry.azurewebsites.net/list-formatting/view-samples/color-picker-format" />