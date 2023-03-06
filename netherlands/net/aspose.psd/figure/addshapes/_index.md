---
title: Figure.AddShapes
second_title: Aspose.PSD voor .NET API-referentie
description: Figure methode. Voegt een reeks vormen toe aan de figuur.
type: docs
weight: 70
url: /nl/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

Voegt een reeks vormen toe aan de figuur.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | Shape[] | De vormen om toe te voegen. |

### Voorbeelden

In dit voorbeeld wordt een nieuwe afbeelding gemaakt en worden verschillende vormen getekend met behulp van Figuren en GraphicsPath op het afbeeldingsoppervlak

```csharp
[C#]

//Maak een exemplaar van Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Maak en initialiseer een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Grafisch oppervlak wissen
    graphics.Clear(Color.Wheat);

    //Maak een instantie van de klasse GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Maak een instantie van de klasse Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Voeg vorm toe aan figuurobject
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Maak een instantie van de klasse Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Voeg vorm toe aan figuurobject
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Voeg figuurobject toe aan GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Teken een pad met een Pen-object in de kleur Zwart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Maak exportopties en initialiseer ze.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // sla alle veranderingen op.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Zie ook

* class [Shape](../../shape/)
* class [Figure](../)
* naamruimte [Aspose.PSD](../../figure/)
* montage [Aspose.PSD](../../../)


