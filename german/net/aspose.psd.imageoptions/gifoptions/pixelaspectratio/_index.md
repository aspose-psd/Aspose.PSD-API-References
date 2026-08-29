---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GifOptions-Eigenschaft. Ruft das Pixel-Seitenverhältnis des GIFs ab oder legt es fest"
type: docs
weight: 90
url: /de/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

Liest oder setzt das Pixel‑Seitenverhältnis des GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

Das Pixel-Seitenverhältnis des GIFs.

## Hinweise

Pixel Aspect Ratio - Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert des Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Das Pixel Aspect Ratio ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich dieses Feldes ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 - Es werden keine Informationen zum Seitenverhältnis angegeben. 1..255 - Wert, der in der Berechnung verwendet wird.

### Siehe auch

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


