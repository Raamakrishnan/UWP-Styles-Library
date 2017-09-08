# Pivot Bottom Header Style
A style to move the `PivotHeader` to the bottom of the Pivot. Can come in handy in phones

## Preview
![Image Preview](PivotBottomHeaderStyle.gif "Image Preview")

## Usage
Checked with **Windows 10 Anniversary Update (14393)**.

> *Note*: When using this style with `PivotHeaderItemAccentUnderlineStyle`, a small change needs to be made to `PivotHeaderItemAccentUnderlineStyle` to move the line to the top.
>
> Change lines 141 - 142 in `PivotHeaderItemAccentUnderlineStyle` as:
>
> ```xaml
> <Rectangle x:Name="UnderScore" HorizontalAlignment="Stretch"
>            VerticalAlignment="Top" Height="2" Visibility="Collapsed" Fill="{ThemeResource SystemControlBackgroundAccentBrush}"/>
> ```