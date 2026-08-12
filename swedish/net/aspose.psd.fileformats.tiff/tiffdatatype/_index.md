---
title: "Klass TiffDataType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Tiff.TiffDataType klass. Den tiff‑datatypen"
type: docs
weight: 4680
url: /sv/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

Tiff-datatypen.

```csharp
public abstract class TiffDataType : IComparable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Hämtar antalet element. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Hämtar heltalsrepresentationen av tagg‑id. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Hämtar ett värde som indikerar om taggdata är giltig. En giltig tagg innehåller data som kan bevaras. En ogiltig tagg kan inte lagras. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Hämtar tagg‑id. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Hämtar taggtypen. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Hämtar eller anger värdet som denna datatyp innehåller. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Läser taggdata. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Utför en djup kloning av denna instans. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Returnerar en String som representerar detta objekt. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Skriver den extra taggdata. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Skriver taggdata. |

### Se även

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


