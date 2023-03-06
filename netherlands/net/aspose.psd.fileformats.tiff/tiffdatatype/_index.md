---
title: Class TiffDataType
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Tiff.TiffDataType klas. Het tiffgegevenstype.
type: docs
weight: 4210
url: /nl/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Het tiff-gegevenstype.

```csharp
public abstract class TiffDataType : IComparable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Krijgt de extra gegevensgrootte in bytes (voor het geval de 12 bytes niet genoeg zijn om in de taggegevens te passen). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Haalt het aantal elementen op. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Krijgt de extra gegevensgrootte in bytes (voor het geval de 12 bytes niet genoeg zijn om in de taggegevens te passen). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Krijgt tag id integer representatie. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Krijgt een waarde die aangeeft of taggegevens geldig zijn. De geldige tag bevat gegevens die behouden kunnen blijven. De ongeldige tag kan niet worden opgeslagen. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Krijgt de tag-id. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Haalt het tagtype op. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Hiermee wordt de waarde van dit gegevenstype opgehaald of ingesteld. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Leest de taggegevens. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Vergelijkt de huidige instantie met een ander object van hetzelfde type en retourneert een geheel getal dat aangeeft of de huidige instantie voorafgaat aan, volgt op of voorkomt op dezelfde positie in de sorteervolgorde als het andere object. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Voert een diepe kloon uit van deze instantie. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Schrijft de aanvullende taggegevens. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Schrijft de taggegevens. |

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* montage [Aspose.PSD](../../)


