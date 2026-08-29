---
title: "GifOptions.ColorResolution"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GifOptions-Eigenschaft. Gibt die GIF-Farbauflösung zurück oder legt sie fest"
type: docs
weight: 30
url: /de/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

Liest oder setzt die Farbauflösung des GIF.

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

Die Farbauflösung.

## Hinweise

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben der Grafik ausgewählt wurden, nicht die Anzahl der tatsächlich in der Grafik verwendeten Farben. Beispiel: Wenn der Wert in diesem Feld 3 ist, hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Bildgenerierung. Dieser Wert sollte gesetzt werden, um den Reichtum der Originalpalette anzugeben, selbst wenn nicht jede Farbe der gesamten Palette auf dem Quellgerät verfügbar ist. Der zulässige Wertebereich liegt zwischen 0 und 1000.

### Siehe auch

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


