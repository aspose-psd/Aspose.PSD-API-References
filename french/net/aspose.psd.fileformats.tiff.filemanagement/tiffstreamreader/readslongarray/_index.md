---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode TiffStreamReader. Lit un tableau de valeurs entières signées depuis le flux"
type: docs
weight: 140
url: /fr/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Lit un tableau de valeurs entières signées depuis le flux.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| position | Int64 | La position à lire. |
| count | Int64 | Le nombre d'éléments. |

### Valeur de retour

Le tableau de valeurs entières signées.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | count;Le nombre total d'octets est négatif. + count + x4= + totalBytes |

### Voir aussi

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


