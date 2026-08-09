---
title: "Classe TiffDataType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Tiff.TiffDataType. Le type de données TIFF."
type: docs
weight: 4680
url: /fr/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

Le type de données tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Obtient la taille supplémentaire des données en octets (au cas où les 12 octets ne seraient pas suffisants pour contenir les données de l'étiquette). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Obtient le nombre d'éléments. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Obtient la taille supplémentaire des données en octets (au cas où les 12 octets ne seraient pas suffisants pour contenir les données de l'étiquette). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Obtient la représentation entière de l'identifiant de l'étiquette. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Obtient une valeur indiquant si les données de l'étiquette sont valides. L'étiquette valide contient des données qui peuvent être conservées. L'étiquette invalide ne peut pas être stockée. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Obtient l'identifiant de l'étiquette. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Obtient le type de l'étiquette. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Obtient ou définit la valeur que ce type de données contient. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Lit les données de l'étiquette. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Effectue un clonage profond de cette instance. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Renvoie une chaîne qui représente cette instance. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Écrit les données de balise supplémentaires. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Écrit les données de balise. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


