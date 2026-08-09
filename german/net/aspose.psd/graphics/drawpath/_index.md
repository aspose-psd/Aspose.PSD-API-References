---
title: "Graphics.DrawPath"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet einen GraphicsPath."
type: docs
weight: 280
url: /de/net/aspose.psd/graphics/drawpath/
---
{{< psd/tize >}}
## Graphics.DrawPath method

Zeichnet einen [`GraphicsPath`](../../graphicspath/).

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil des Pfads bestimmt. |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/) zum Zeichnen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *path* ist null. |

## Beispiele

Dieses Beispiel verwendet die Klassen GraphicsPath und Graphics, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Das Beispiel erstellt ein neues Bild und zeichnet Pfade mit Hilfe der Klasse GraphicsPath. Am Ende wird die von der Klasse Graphics bereitgestellte Methode DrawPath aufgerufen, um die Pfade auf der Oberfläche zu rendern. Schließlich wird das Bild in das Tiff-Dateiformat exportiert.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Füge Formen zum Figure-Objekt hinzu
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Füge das Figure-Objekt zu GraphicsPath hinzu
    graphicspath.AddFigure(figure);

    //Zeichne Pfad mit Pen-Objekt in der Farbe Schwarz
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Speichere alle Änderungen.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Siehe auch

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


