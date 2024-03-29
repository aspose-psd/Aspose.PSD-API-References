---
title: GifOptions.ColorResolution
second_title: Aspose.PSD für .NET-API-Referenz
description: GifOptions eigendom. Ruft die GIFFarbauflösung ab oder legt sie fest.
type: docs
weight: 30
url: /de/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
## GifOptions.ColorResolution property

Ruft die GIF-Farbauflösung ab oder legt sie fest.

```csharp
public byte ColorResolution { get; set; }
```

### Eigentumswert

Die Farbauflösung.

### Bemerkungen

Farbauflösung - Anzahl der verfügbaren Bits pro Primärfarbe für das Originalbild minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben in der Grafik ausgewählt wurden, nicht die Anzahl der tatsächlich in der Grafik verwendeten Farben. Wenn der Wert in diesem Feld beispielsweise 3 ist, dann hatte die Palette von des Originalbildes 4 Bits pro Primärfarbe, die verfügbar waren, um das Bild zu erstellen. Dieser Wert sollte so eingestellt werden, dass er den Reichtum der Originalpalette angibt, auch wenn nicht jede Farbe aus der gesamten -Palette auf dem Quellcomputer verfügbar ist.

### Siehe auch

* class [GifOptions](../)
* namensraum [Aspose.PSD.ImageOptions](../../gifoptions/)
* Montage [Aspose.PSD](../../../)


