---
title: "Klasse StreamSource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Sources.StreamSource Klasse. Stellt eine Stream-Quelle dar"
type: docs
weight: 6120
url: /de/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

Stellt eine Stream‑Quelle dar.

```csharp
public sealed class StreamSource : Source
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz der `StreamSource`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Ermittelt einen Wert, der angibt, ob der Stream freigegeben werden soll, sobald der Container freigegeben wird. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Ermittelt den Stream. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Ermittelt den Stream-Container. |

## Beispiele

Dieses Beispiel verwendet die Graphics class, um primitive Formen auf der Image Oberfläche zu erstellen. Um den Vorgang zu demonstrieren, erstellt das Beispiel ein neues Image im PSD‑Format und zeichnet primitive Formen auf der Image Oberfläche mithilfe der von der Graphics class bereitgestellten Draw‑Methoden, um es anschließend in das PSD‑Dateiformat zu exportieren.

```csharp
[C#]

//Erstelle eine Instanz von Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Zeichnen Sie einen Bogen, indem Sie das Pen‑Objekt mit schwarzer Farbe angeben, 
    //ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep‑Winkel
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Zeichnen Sie eine Bézier-Kurve, indem Sie das Pen‑Objekt mit blauer Farbe und Koordinatenpunkten angeben.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Zeichnen Sie eine Kurve, indem Sie das Pen‑Objekt mit grüner Farbe und einem Array von Punkten angeben
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Zeichnen Sie eine Ellipse mit dem Pen‑Objekt und einem umgebenden Rechteck
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Zeichnen Sie eine Linie 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Zeichnen Sie ein Kuchen‑Segment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Zeichnen Sie ein Polygon, indem Sie das Pen‑Objekt mit roter Farbe und einem Array von Punkten angeben
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Zeichnen Sie ein Rechteck
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Erstellen Sie ein SolidBrush‑Objekt und setzen Sie dessen verschiedene Eigenschaften
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Zeichnen Sie einen String mit dem SolidBrush-Objekt und Font an einem bestimmten Punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Erstellen Sie eine Instanz von PngOptions und setzen Sie deren verschiedene Eigenschaften
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Speichere alle Änderungen.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Siehe auch

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


