---
title: ArcShape
second_title: Aspose.PSD für .NET-API-Referenz
description: Stellt eine Bogenform dar.
type: docs
weight: 5390
url: /de/net/aspose.psd.shapes/arcshape/
---
## ArcShape class

Stellt eine Bogenform dar.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ArcShape](arcshape#constructor)() | Initialisiert eine neue Instanz von[`ArcShape`](../arcshape) Klasse. |
| [ArcShape](arcshape#constructor_1)(RectangleF, float, float) | Initialisiert eine neue Instanz von[`ArcShape`](../arcshape) Klasse. |
| [ArcShape](arcshape#constructor_2)(RectangleF, float, float, bool) | Initialisiert eine neue Instanz von[`ArcShape`](../arcshape) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds) { get; } | Ruft die Grenzen des Objekts ab. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center) { get; } | Ruft den Mittelpunkt der Form ab. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint) { get; } | Ruft den Endformpunkt ab. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments) { get; } | Ruft einen Wert ab, der angibt, ob die Form Segmente hat. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die geordnete Form geschlossen ist. Bei der Verarbeitung geschlossen geordneter Formen haben die Start- und Endpunkte keine Bedeutung. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom) { get; } | Ruft den linken unteren Rechteckpunkt ab. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop) { get; } | Ruft den linken oberen Rechteckpunkt ab. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight) { get; } | Ruft die Rechteckhöhe ab. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Ruft die Breite des Rechtecks ab. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom) { get; } | Ruft den rechten unteren Rechteckpunkt ab. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop) { get; } | Ruft den rechten oberen Rechteckpunkt ab. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments) { get; } | Ruft die Formsegmente ab. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle) { get; set; } | Ruft den Startwinkel ab oder legt ihn fest. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint) { get; } | Ruft den Anfangsformpunkt ab. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle) { get; set; } | Ruft den Sweep-Winkel ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds#getbounds)(Matrix) | Ruft die Grenzen des Objekts ab. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds#getbounds_1)(Matrix, Pen) | Ruft die Grenzen des Objekts ab. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse)() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

### Beispiele

Dieses Beispiel erstellt ein neues Image und zeichnet eine Vielzahl von Formen mithilfe von Figures und GraphicsPath auf der Image-Oberfläche

```csharp
[C#]

//Eine Instanz von Image erstellen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Eine Instanz der Graphics-Klasse erstellen und initialisieren
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafikoberfläche löschen
    graphics.Clear(Color.Wheat);

    //Eine Instanz der GraphicsPath-Klasse erstellen
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Eine Instanz der Figure-Klasse erstellen
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Shape zum Figure-Objekt hinzufügen
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Eine Instanz der Figure-Klasse erstellen
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Shape zum Figure-Objekt hinzufügen
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Figure-Objekt zu GraphicsPath hinzufügen
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Exportoptionen erstellen und initialisieren.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Alle Änderungen speichern.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Siehe auch

* class [PieShape](../pieshape)
* interface [IOrderedShape](../../aspose.psd/iorderedshape)
* namensraum [Aspose.PSD.Shapes](../../aspose.psd.shapes)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
