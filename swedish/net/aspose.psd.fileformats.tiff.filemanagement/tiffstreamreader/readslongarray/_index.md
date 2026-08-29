---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD för .NET API‑referens"
description: "TiffStreamReader metod. Läser en array av signerade heltalsvärden från strömmen"
type: docs
weight: 140
url: /sv/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Läser en matris av signerade heltalsvärden från strömmen.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | Int64 | Positionen att läsa från. |
| count | Int64 | Antalet element. |

### Returvärde

Arrayen med signerade heltalsvärden.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | count;Totalt byteantal är negativt. + count + x4= + totalBytes |

### Se även

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


