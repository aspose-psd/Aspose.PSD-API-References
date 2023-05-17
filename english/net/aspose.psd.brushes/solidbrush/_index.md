---
title: Class SolidBrush
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Brushes.SolidBrush class. Solid brush is intended for drawing continiously with specific color. This class cannot be inherited
type: docs
weight: 200
url: /net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Solid brush is intended for drawing continiously with specific color. This class cannot be inherited.

```csharp
public sealed class SolidBrush : Brush
```

## Constructors

| Name | Description |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Initializes a new instance of the `SolidBrush` class. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Initializes a new instance of the `SolidBrush` class. |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Gets or sets the brush color. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |

## Methods

| Name | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Creates a new deep clone of the current [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |

## Examples

This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PSD format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class then export it to PSD file format.

```csharp
[C#]

//Create an instance of Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear Graphics surface
    graphics.Clear(Color.Wheat);

    //Draw an Arc by specifying the Pen object having Black color, 
    //a Rectangle surrounding the Arc, Start Angle and Sweep Angle
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Draw a Curve by specifying the Pen object having Green color and an array of Points
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Draw an Ellipse using the Pen object and a surrounding Rectangle
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Draw a Line 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Draw a Pie segment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Draw a Polygon by specifying the Pen object having Red color and an array of Points
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Draw a Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Create a SolidBrush object and set its various properties
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Draw a String using the SolidBrush object and Font, at specific Point
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Create an instance of PngOptions and set its various properties
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // save all changes.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### See Also

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


