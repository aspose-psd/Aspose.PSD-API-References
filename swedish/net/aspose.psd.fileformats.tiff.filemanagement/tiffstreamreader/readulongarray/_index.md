---
title: "TiffStreamReader.ReadULongArray"
second_title: "Aspose.PSD för .NET API‑referens"
description: "TiffStreamReader-metod. Läser en array av osignerade heltalsvärden från strömmen."
type: docs
weight: 200
url: /sv/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadULongArray method

Läser en matris av osignerade heltalsvärden från strömmen.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | Int64 | Positionen att läsa från. |
| count | Int64 | Antalet element. |

### Returvärde

Arrayen av osignerade heltalsvärden.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | count;Totalt byteantal är negativt. + count + x4= + totalBytes |

### Se även

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


