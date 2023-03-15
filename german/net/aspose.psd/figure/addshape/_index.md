---
title: Figure.AddShape
second_title: Aspose.PSD für .NET-API-Referenz
description: Figure methode. Fügt der Figur eine Form hinzu.
type: docs
weight: 60
url: /de/net/aspose.psd/figure/addshape/
---
## Figure.AddShape method

Fügt der Figur eine Form hinzu.

```csharp
public void AddShape(Shape shape)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | Shape | Die hinzuzufügende Form. |

### Beispiele

Dieses Beispiel verwendet GraphicsPath und die Graphics-Klasse, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Beispiel erstellt ein neues Bild und zeichnet Pfade mit Hilfe der GraphicsPath-Klasse. Am Ende wird die DrawPath-Methode aufgerufen, die von der Graphics-Klasse bereitgestellt wird, um die Pfade auf der Oberfläche zu rendern. Schließlich wird das Bild in das Tiff-Dateiformat exportiert.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Formen zum Figurobjekt hinzufügen
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure-Objekt zu GraphicsPath hinzufügen
    graphicspath.AddFigure(figure);

    // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Eine Instanz von TiffOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Alle Änderungen speichern.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Siehe auch

* class [Shape](../../shape/)
* class [Figure](../)
* namensraum [Aspose.PSD](../../figure/)
* Montage [Aspose.PSD](../../../)


