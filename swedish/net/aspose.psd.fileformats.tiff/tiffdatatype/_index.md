---
title: Class TiffDataType
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Tiff.TiffDataType klass. tiffdatatypen.
type: docs
weight: 4210
url: /sv/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

tiff-datatypen.

```csharp
public abstract class TiffDataType : IComparable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Hämtar den extra datastorleken i byte (om de 12 byten inte räcker för att passa taggdata). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Hämtar antalet element. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Hämtar den extra datastorleken i byte (om de 12 byten inte räcker för att passa taggdata). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Får tagg-id heltalsrepresentation. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Får ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Hämtar tagg-id. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Hämtar taggtypen. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Hämtar eller ställer in värdet som denna datatyp innehåller. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Läser taggdata. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer efter eller förekommer i samma position i sorteringsordningen som det andra objektet. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Utför en djup klon av denna instans. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Returnerar enString som representerar denna instans. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Skriver ytterligare taggdata. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Skriver taggdata. |

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* hopsättning [Aspose.PSD](../../)


