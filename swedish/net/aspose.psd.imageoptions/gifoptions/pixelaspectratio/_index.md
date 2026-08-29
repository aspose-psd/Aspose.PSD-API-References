---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GifOptions egenskap. Hämtar eller anger GIF:s pixelaspektförhållande"
type: docs
weight: 90
url: /sv/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

Hämtar eller anger GIF:s pixelaspektförhållande.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF:s pixelaspektförhållande.

## Anmärkningar

Pixel Aspect Ratio – Faktor som används för att beräkna en approximation av pixelns bildförhållande i originalbilden. Om fältets värde inte är 0 beräknas denna approximation av bildförhållandet enligt formeln: Bildförhållande = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio definieras som kvoten av pixelns bredd över dess höjd. Värdeintervallet i detta fält tillåter specifikation av den bredaste pixeln 4:1 till den högsta pixeln 1:4 i steg om 1/64. Värden: 0 – Ingen information om bildförhållande ges. 1..255 – Värde som används i beräkningen.

### Se även

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


