---
title: "Klasse SolidBrush"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Brushes.SolidBrush Klasse. Der Solid-Pinsel ist zum kontinuierlichen Zeichnen mit einer bestimmten Farbe vorgesehen. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 200
url: /de/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Der Solid‑Pinsel ist zum kontinuierlichen Zeichnen mit einer bestimmten Farbe gedacht. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class SolidBrush : Brush
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Initialisiert eine neue Instanz der `SolidBrush` Klasse. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Initialisiert eine neue Instanz der `SolidBrush` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Liest oder legt die Farbe des Pinsels fest. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen Deep-Clone des aktuellen [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

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

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


