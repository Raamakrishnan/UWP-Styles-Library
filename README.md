# UWP Styles Library
Just a collection of some cool styles that you can just add on to your next UWP project!

## The Collection
* [Custom App Bar Toggle Button](/CustomAppBarToggleButtonStyle)
* [Rounded Button Style](/RoundedButtonStyle)
* [Pivot Styles](/Pivot)
* [Icon In Secondary App Bar Button Style](/IconInSecondaryAppBarButtonStyle)
* [Circle Button Style](/CircleButtonStyle)
* [Progress Ring Styles](/ProgressRingStyles)

## Usage
The XAML Resource dictionary containing the style will be given here. Add it to your project the usual way!

Just for reference:
https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/resourcedictionary-and-xaml-resource-references#merged-resource-dictionaries

## Conventions
### Naming
> `<ControlName> <StyleName> Style <Index>`

`ControlName` - Name of the control for which this style can be applied
`StyleName` - A descriptive name of the style
`Index` - An index is used to number similar named styles

`StyleName` and `Index` are optional. Generally, any one of them should be mentioned

Ex. `ProgressRingStyle1`:

`ProgressRing` - ControlName, `1` - Index

### Organization
* Styles for each Controls are to be kept in separate folders
* If a control can only be used as part of another control, its folder must be placed inside its parent control's folder

Ex. `./Pivot/PivotHeader/`

`Pivot` folder contains styles for Pivot Control. Because PivotHeader can only be used inside a Pivot, `PivotHeader` folder is kept inside `Pivot` folder.

*Note: Conventions are yet to be applied fully*

## License
You can do whatever you want :D

I will be very happy to know that I was of help to you. So, please tell let me know if you ever use this :)