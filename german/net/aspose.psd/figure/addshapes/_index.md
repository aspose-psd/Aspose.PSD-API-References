---
title: Figure.AddShapes
second_title: Aspose.PSD für .NET-API-Referenz
description: Figure methode. Fügt der Figur eine Reihe von Formen hinzu.
type: docs
weight: 70
url: /de/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

Fügt der Figur eine Reihe von Formen hinzu.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | Shape[] | Die hinzuzufügenden Formen. |

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

* class [Shape](../../shape/)
* class [Figure](../)
* namensraum [Aspose.PSD](../../figure/)
* Montage [Aspose.PSD](../../../)


