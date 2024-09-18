---
title: Class Font
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Font class. Defines a particular format for text including font face size and style attributes. This class cannot be inherited
type: docs
weight: 4630
url: /net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

```csharp
public sealed class Font
```

## Constructors

| Name | Description |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initializes a new `Font` that uses the specified existing `Font` and [`FontStyle`](../fontstyle/) enumeration. |
| [Font](font/#constructor_1)(string, float) | Initializes a new `Font` using a specified size. The character set is set to Default, the graphics unit to Point, the font style to Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initializes a new `Font` using a specified size and style. The character set is set to Default, the graphics unit to Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initializes a new `Font` using a specified size and unit. The character set is set to Default, the style is set to Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initializes a new `Font` using a specified size, style, and unit. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initializes a new `Font` using a specified size, style, unit, and character set. |

## Properties

| Name | Description |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Gets a value indicating whether this `Font` is bold. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Gets a byte value that specifies the character set that this `Font` uses. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Gets a value indicating whether this `Font` is italic. |
| [Name](../../aspose.psd/font/name/) { get; } | Gets the face name of this `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | Gets the em-size of this `Font` measured in the units specified by the [`Unit`](./unit/) property. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Gets a value indicating whether this `Font` specifies a horizontal line through the font. |
| [Style](../../aspose.psd/font/style/) { get; } | Gets style information for this `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Gets a value indicating whether this `Font` is underlined. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Gets the unit of measure for this `Font`. |

## Methods

| Name | Description |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Creates an exact deep copy of this `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indicates whether the specified object is a `Font` and has the same property values as this `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Gets the hash code for this `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | Returns a human-readable string representation of this `Font`. |

## Examples

This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface. The example creates a new Image and draw shapes using Figures and GraphicsPath

```csharp
[C#]

//Creates an instance of Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Creates and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clears Graphics surface
    graphics.Clear(Color.Wheat);

    //Creates an instance of Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Create an instance of SolidBrush having Red Color
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Draw a String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // create export options.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // save all changes
    image.Save("C:\\temp\\output.gif", options);
}
```

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


