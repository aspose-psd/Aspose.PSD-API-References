---
title: Class HatchBrush
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Brushes.HatchBrush klas. Definiert einen rechteckigen Pinsel mit einem Schraffurstil einer Vordergrundfarbe und einer Hintergrundfarbe. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 130
url: /de/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Definiert einen rechteckigen Pinsel mit einem Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class HatchBrush : Brush
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Ruft die Farbe der Zwischenräume zwischen den Schraffurlinien ab oder legt sie fest. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Ruft die Farbe der Schraffurlinien ab oder legt sie fest. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Ruft den Schraffurstil dieses Pinsels ab oder legt ihn fest. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass der Pinsel vollständig sichtbar ist, der Wert 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Erstellt einen neuen tiefen Klon des aktuellen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |

### Beispiele

Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Bild und zeichnet Rechtecke auf der Bildoberfläche.

```csharp
[C#]

//Eine Instanz von Image erstellen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Eine Instanz von Graphics erstellen und mit dem Image-Objekt initialisieren
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Löschen Sie die Grafikoberfläche mit weißer Farbe
    graphics.Clear(Aspose.PSD.Color.White);

    // Erstellen Sie eine Instanz von Pen mit der Farbe Rot und der Breite 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Eine Instanz von HatchBrush erstellen und ihre Eigenschaften festlegen
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Eine Instanz von Pen erstellen
    // mit HatchBrush-Objekt und -Breite initialisieren
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Zeichne Rechtecke durch Angabe des Pen-Objekts
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Zeichne Rechtecke durch Angabe des Pen-Objekts
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Exportoptionen erstellen und initialisieren.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Alle Änderungen speichern.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Siehe auch

* class [Brush](../../aspose.psd/brush/)
* namensraum [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* Montage [Aspose.PSD](../../)


