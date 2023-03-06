---
title: TiffStreamReader.ReadSLongArray
second_title: Aspose.PSD voor .NET API-referentie
description: TiffStreamReader methode. Leest een array van integerwaarden met teken uit de stream.
type: docs
weight: 140
url: /nl/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
## TiffStreamReader.ReadSLongArray method

Leest een array van integer-waarden met teken uit de stream.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | Int64 | De positie om uit te lezen. |
| count | Int64 | De elementen tellen. |

### Winstwaarde

De array van integer-waarden met teken.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | count;totaal aantal bytes is negatief. + aantal + x4= + totaalBytes |

### Zie ook

* class [TiffStreamReader](../)
* naamruimte [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* montage [Aspose.PSD](../../../)


