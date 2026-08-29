---
title: "Enum CompressionMethod"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod enum. Définit la méthode de compression utilisée pour les données d'image."
type: docs
weight: 1630
url: /fr/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Définit la méthode de compression utilisée pour les données d'image.

```csharp
public enum CompressionMethod : short
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Raw | `0` | Pas de compression. Les données d'image sont stockées sous forme d'octets bruts en ordre planaire RGBA. Cela signifie que d'abord toutes les données R sont écrites, puis toutes les données G, ensuite toutes les données B et enfin toutes les données A. |
| RLE | `1` | Les données d'image compressées en RLE commencent par les comptes d'octets pour toutes les lignes de balayage (lignes * canaux), chaque compte étant stocké sur deux octets. Les données compressées en RLE suivent, chaque ligne de balayage étant compressée séparément. La compression RLE utilise le même algorithme de compression que la routine PackBits du ROM Macintosh et la norme TIFF. |
| ZipWithoutPrediction | `2` | ZIP sans prédiction. |
| ZipWithPrediction | `3` | ZIP avec prédiction. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


