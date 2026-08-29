---
title: "Figure.AddShapes"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Figure-Methode. Fügt der Figur einen Bereich von Formen hinzu"
type: docs
weight: 70
url: /de/net/aspose.psd/figure/addshapes/
---
{{< psd/tize >}}
## Figure.AddShapes method

Fügt der Figur einen Bereich von Formen hinzu.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Formen | Shape[] | Die hinzuzufügenden Formen. |

## Beispiele

Dieses Beispiel erstellt ein neues Image und zeichnet eine Vielzahl von Formen mithilfe von Figures und GraphicsPath auf der Image-Oberfläche.

```csharp
[C#]

//Erstelle eine Instanz von Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Erstelle eine Instanz der Klasse GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Erstelle eine Instanz der Klasse Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Form zum Figure-Objekt hinzufügen
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Erstelle eine Instanz der Klasse Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Form zum Figure-Objekt hinzufügen
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Füge das Figure-Objekt zu GraphicsPath hinzu
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Zeichne Pfad mit Pen-Objekt in der Farbe Schwarz
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Erstelle Exportoptionen und initialisiere sie.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Speichere alle Änderungen.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Siehe auch

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


