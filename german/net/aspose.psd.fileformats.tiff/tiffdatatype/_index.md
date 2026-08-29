---
title: "Klasse TiffDataType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Tiff.TiffDataType Klasse. Der TIFF-Datentyp"
type: docs
weight: 4680
url: /de/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

Der Tiff-Datentyp.

```csharp
public abstract class TiffDataType : IComparable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Gibt die zusätzliche Datengröße in Bytes zurück (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Gibt die Anzahl der Elemente zurück. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Gibt die zusätzliche Datengröße in Bytes zurück (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Gibt die ganzzahlige Darstellung der Tag-ID zurück. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Gibt einen Wert zurück, der angibt, ob Tag-Daten gültig sind. Der gültige Tag enthält Daten, die erhalten werden können. Der ungültige Tag kann nicht gespeichert werden. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Gibt die Tag-ID zurück. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Gibt den Tag-Typ zurück. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Liest oder setzt den Wert, den dieser Datentyp enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Liest die Tag-Daten. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, folgt oder an derselben Position in der Sortierreihenfolge wie das andere Objekt liegt. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Erstellt eine tiefe Kopie dieser Instanz. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Schreibt die zusätzlichen Tag-Daten. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Schreibt die Tag-Daten. |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


