---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété TiffOptions. Obtient ou définit la table de couleurs"
type: docs
weight: 70
url: /fr/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Obtient ou définit la table de couleurs.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

La table de couleurs.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | valeur |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | La table de couleurs ne peut être définie que pour des échantillons par pixel égaux à 1 uniquement. ou les bits par échantillon ne sont pas définis. |
| ArgumentOutOfRangeException | valeur;La longueur du tableau doit correspondre à la formule suivante : 3 * (2**BitsPerSample). |

### Voir aussi

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


