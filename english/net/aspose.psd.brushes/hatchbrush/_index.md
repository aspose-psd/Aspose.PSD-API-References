---
title: Class HatchBrush
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Brushes.HatchBrush class. Defines a rectangular brush with a hatch style a foreground color and a background color. This class cannot be inherited
type: docs
weight: 130
url: /net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Defines a rectangular brush with a hatch style, a foreground color, and a background color. This class cannot be inherited.

```csharp
public sealed class HatchBrush : Brush
```

## Constructors

| Name | Description |
| --- | --- |
| [HatchBrush](hatchbrush/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Gets or sets the color of spaces between the hatch lines. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Gets or sets the color of hatch lines. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Gets or sets the hatch style of this brush. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Creates a new deep clone of the current [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |

## Examples

This example shows the creation and usage Pen objects. The example creates a new Image and draws Rectangles on Image surface.

```csharp
[C#]

//Create an instance of Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create an instance of Graphics and initialize it with Image object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear the Graphics sutface with White Color
    graphics.Clear(Aspose.PSD.Color.White);

    //Create an instance of Pen with color Red and width 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Create an instance of HatchBrush and set its properties
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Create an instance of Pen
    //initialize it with HatchBrush object and width
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Draw Rectangles by specifying Pen object
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Create export options and initialize them.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // save all changes.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### See Also

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


