---
title: Class StreamSource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Sources.StreamSource klas. Repräsentiert eine StreamQuelle.
type: docs
weight: 5620
url: /de/net/aspose.psd.sources/streamsource/
---
## StreamSource class

Repräsentiert eine Stream-Quelle.

```csharp
public sealed class StreamSource : Source
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Initialisiert eine neue Instanz von`StreamSource` Klasse. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz von`StreamSource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Ruft einen Wert ab, der angibt, ob der Stream verworfen werden soll, wenn der Container verworfen wird. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Ruft den Stream ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Ruft den Stream-Container ab. |

### Beispiele

Dieses Beispiel verwendet die Graphics-Klasse, um primitive Formen auf der Image-Oberfläche zu erstellen. Um den Vorgang zu demonstrieren, erstellt das Beispiel ein neues Bild im PSD-Format und zeichnet primitive Formen auf der Bildoberfläche mit Draw-Methoden, die von der Graphics-Klasse verfügbar gemacht werden, und exportiert es dann in das PSD-Dateiformat.

```csharp
[C#]

//Eine Instanz von Image erstellen 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Eine Instanz der Graphics-Klasse erstellen und initialisieren
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafikoberfläche löschen
    graphics.Clear(Color.Wheat);

    //Zeichnen Sie einen Bogen, indem Sie das Stiftobjekt mit schwarzer Farbe angeben, 
    //ein Rechteck, das den Bogen, den Startwinkel und den Sweep-Winkel umgibt
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Zeichnen Sie einen Bezier, indem Sie das Stiftobjekt mit blauer Farbe und Koordinatenpunkten angeben.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Zeichnen Sie eine Kurve, indem Sie das Stiftobjekt mit grüner Farbe und einem Array von Punkten angeben
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Zeichne eine Ellipse mit dem Pen-Objekt und einem umgebenden Rectangle
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Zeichne eine Linie 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // Zeichne ein Kreissegment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Zeichnen Sie ein Polygon, indem Sie das Stiftobjekt mit roter Farbe und einem Array von Punkten angeben
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Zeichne ein Rechteck
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Ein SolidBrush-Objekt erstellen und seine verschiedenen Eigenschaften festlegen
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Zeichne einen String mit dem SolidBrush-Objekt und der Schriftart an einem bestimmten Punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Eine Instanz von PngOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Alle Änderungen speichern.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Siehe auch

* class [Source](../../aspose.psd/source/)
* namensraum [Aspose.PSD.Sources](../../aspose.psd.sources/)
* Montage [Aspose.PSD](../../)


