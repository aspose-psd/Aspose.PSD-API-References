---
title: "TiffStreamReader.ReadULongArray"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode TiffStreamReader. Lit un tableau de valeurs d'entiers non signés depuis le flux"
type: docs
weight: 200
url: /fr/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadULongArray method

Lit un tableau de valeurs entières non signées depuis le flux.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| position | Int64 | La position à lire. |
| count | Int64 | Le nombre d'éléments. |

### Valeur de retour

Le tableau de valeurs d'entiers non signés.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | count;Le nombre total d'octets est négatif. + count + x4= + totalBytes |

### Voir aussi

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


