---
title: GraphicsPath.AddFigure
second_title: Aspose.PSD for .NET API Reference
description: GraphicsPath method. Adds a new figure
type: docs
weight: 50
url: /net/aspose.psd/graphicspath/addfigure/
---
{{< psd/tize >}}
## GraphicsPath.AddFigure method

Adds a new figure.

```csharp
public void AddFigure(Figure figure)
```

| Parameter | Type | Description |
| --- | --- | --- |
| figure | Figure | The figure to add. |

## Examples

This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image and draws paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface. Finally image is exported to Tiff file format.

```csharp
[C#]

//Create an instance of Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear Graphics surface
    graphics.Clear(Color.Wheat);

    //Create an instance of GraphicsPath class
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Create an instance of Figure class
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Add Shapes to Figure object
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Add Figure object to GraphicsPath
    graphicspath.AddFigure(figure);

    //Draw path with Pen object of color Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Create an instance of TiffOptions and set its various properties
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // save all changes.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### See Also

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


