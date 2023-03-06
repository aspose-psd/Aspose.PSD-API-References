---
title: Class RectangleShape
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Shapes.RectangleShape klas. Vertegenwoordigt een rechthoekige vorm.
type: docs
weight: 5530
url: /nl/net/aspose.psd.shapes/rectangleshape/
---
## RectangleShape class

Vertegenwoordigt een rechthoekige vorm.

```csharp
public class RectangleShape : RectangleProjectedShape
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | Initialiseert een nieuw exemplaar van het`RectangleShape` klasse. |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | Initialiseert een nieuw exemplaar van het`RectangleShape` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Haalt de grenzen van het object op. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Haalt het middelpunt van de vorm op. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Krijgt een waarde die aangeeft of vorm segmenten heeft. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Krijgt het rechthoekpunt linksonder. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Krijgt het rechthoekpunt linksboven. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Krijgt de hoogte van de rechthoek. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Haalt de breedte van de rechthoek op. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Krijgt het punt van de rechthoek rechtsonder. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Krijgt het punt van de rechterbovenhoek. |
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | Krijgt de vormsegmenten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Haalt de grenzen van het object op. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Haalt de grenzen van het object op. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Past de opgegeven transformatie toe op de vorm. |

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

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* naamruimte [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* montage [Aspose.PSD](../../)


