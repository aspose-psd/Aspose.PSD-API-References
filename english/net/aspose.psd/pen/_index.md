---
title: Class Pen
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Pen class. Defines an object used to draw lines curves and figures
type: docs
weight: 5390
url: /net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Defines an object used to draw lines, curves and figures.

```csharp
public class Pen : TransparencySupporter
```

## Constructors

| Name | Description |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initializes a new instance of the `Pen` class with the specified [`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | Initializes a new instance of the `Pen` class with the specified color. |
| [Pen](pen/#constructor_1)(Brush, float) | Initializes a new instance of the `Pen` class with the specified [`Brush`](./brush/) and [`Width`](./width/). |
| [Pen](pen/#constructor_3)(Color, float) | Initializes a new instance of the `Pen` class with the specified [`Color`](./color/) and [`Width`](./width/) properties. |

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Gets or sets the alignment for this `Pen`. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Gets or sets the [`Brush`](./brush/) that determines attributes of this `Pen`. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Gets or sets the color of this `Pen`. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Gets or sets a custom cap to use at the end of lines drawn with this `Pen`. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Gets or sets a custom cap to use at the beginning of lines drawn with this `Pen`. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Gets or sets the cap style used at the end of the dashes that make up dashed lines drawn with this `Pen`. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Gets or sets the distance from the start of a line to the beginning of a dash pattern. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Gets or sets an array of custom dashes and spaces. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Gets or sets the style used for dashed lines drawn with this `Pen`. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Gets or sets the cap style used at the end of lines drawn with this `Pen`. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Gets or sets the join style for the ends of two consecutive lines drawn with this `Pen`. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Gets or sets the limit of the thickness of the join on a mitered corner. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Gets or sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Gets the style of lines drawn with this `Pen`. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Gets or sets the cap style used at the beginning of lines drawn with this `Pen`. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Gets or sets a copy of the geometric transformation for this `Pen`. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Gets or sets the width of this `Pen`, in units of the Graphics object used for drawing. |

## Methods

| Name | Description |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplies the transformation matrix for this `Pen` by the specified [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplies the transformation matrix for this `Pen` by the specified [`Matrix`](../matrix/) in the specified order. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Resets the geometric transformation matrix for this `Pen` to identity. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Scales the local geometric transformation by the specified factors in the specified order. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Sets the values that determine the style of cap used to end lines drawn by this `Pen`. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Translates the local geometric transformation by the specified dimensions in the specified order. |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


