---
title: TiffStreamReader.ReadULongArray
second_title: Aspose.PSD voor .NET API-referentie
description: TiffStreamReader methode. Leest een array van integerwaarden zonder teken uit de stream.
type: docs
weight: 200
url: /nl/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
## TiffStreamReader.ReadULongArray method

Leest een array van integerwaarden zonder teken uit de stream.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | Int64 | De positie om uit te lezen. |
| count | Int64 | De elementen tellen. |

### Winstwaarde

De array van integerwaarden zonder teken.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | count;totaal aantal bytes is negatief. + aantal + x4= + totaalBytes |

### Zie ook

* class [TiffStreamReader](../)
* naamruimte [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* montage [Aspose.PSD](../../../)


