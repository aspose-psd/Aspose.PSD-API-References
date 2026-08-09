---
title: "Klasse HatchBrush"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Brushes.HatchBrush Klasse. Definiert einen rechteckigen Pinsel mit einem Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 130
url: /de/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Definiert einen rechteckigen Pinsel mit Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class HatchBrush : Brush
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Ruft ab oder legt die Farbe der Zwischenräume zwischen den Schraffurlinien fest. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Ruft ab oder legt die Farbe der Schraffurlinien fest. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Ruft ab oder legt den Schraffurstil dieses Pinsels fest. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen Deep-Clone des aktuellen [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

## Beispiele

Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Image und zeichnet Rechtecke auf der Image-Oberfläche.

```csharp
[C#]

//Erstelle eine Instanz von Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle eine Instanz von Graphics und initialisiere sie mit einem Image-Objekt
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche mit weißer Farbe.
    graphics.Clear(Aspose.PSD.Color.White);

    //Erstelle eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Erstelle eine Instanz von HatchBrush und setze ihre Eigenschaften
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Erstelle eine Instanz von Pen
    //initialisiere sie mit einem HatchBrush-Objekt und einer Breite
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Zeichne Rechtecke, indem du ein Pen-Objekt angibst
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Zeichne Rechtecke, indem du ein Pen-Objekt angibst
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Erstelle Exportoptionen und initialisiere sie.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Speichere alle Änderungen.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Siehe auch

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


