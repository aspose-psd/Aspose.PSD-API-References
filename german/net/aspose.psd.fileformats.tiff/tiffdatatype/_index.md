---
title: Class TiffDataType
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Tiff.TiffDataType klas. Der TIFFDatentyp.
type: docs
weight: 4210
url: /de/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Der TIFF-Datentyp.

```csharp
public abstract class TiffDataType : IComparable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Ruft die zusätzliche Datengröße in Bytes ab (falls die 12 Bytes nicht ausreichen, um die Tag-Daten aufzunehmen). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Ruft die Anzahl der Elemente ab. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Ruft die zusätzliche Datengröße in Bytes ab (falls die 12 Bytes nicht ausreichen, um die Tag-Daten aufzunehmen). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Ruft die ganzzahlige Darstellung der Tag-ID ab. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Ruft einen Wert ab, der angibt, ob Tag-Daten gültig sind. Das gültige Tag enthält Daten, die bewahrt werden können. Das ungültige Tag kann nicht gespeichert werden. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Ruft die Tag-ID ab. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Ruft den Tag-Typ ab. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Liest oder setzt den Wert, den dieser Datentyp enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Liest die Tag-Daten. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Vergleicht die aktuelle Instanz mit einem anderen Objekt des gleichen Typs und gibt eine ganze Zahl zurück, die angibt, ob die aktuelle Instanz in der Sortierreihenfolge an der gleichen Position wie das andere Objekt vorangeht, folgt oder an derselben Position vorkommt. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Führt einen tiefen Klon dieser Instanz durch. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Schreibt die zusätzlichen Tag-Daten. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Schreibt die Tag-Daten. |

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* Montage [Aspose.PSD](../../)


