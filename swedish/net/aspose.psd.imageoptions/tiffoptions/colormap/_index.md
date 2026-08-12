---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD för .NET API‑referens"
description: "TiffOptions-egenskap. Hämtar eller anger färgkartan"
type: docs
weight: 70
url: /sv/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Hämtar eller anger färgkartan.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

Färgkartan.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | värde |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Färgkartan kan endast definieras för prover per pixel lika med 1. eller Bitar per prov är inte definierade. |
| ArgumentOutOfRangeException | värde;Arrayens längd måste motsvara följande formel: 3 * (2**BitsPerSample). |

### Se även

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


