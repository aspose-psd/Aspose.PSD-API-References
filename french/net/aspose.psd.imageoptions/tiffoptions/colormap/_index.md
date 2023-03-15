---
title: TiffOptions.ColorMap
second_title: Référence de l'API Aspose.PSD pour .NET
description: TiffOptions propriété. Obtient ou définit la palette de couleurs.
type: docs
weight: 70
url: /fr/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Obtient ou définit la palette de couleurs.

```csharp
public ushort[] ColorMap { get; set; }
```

### Valeur de la propriété

La carte des couleurs.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | valeur |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | La palette de couleurs peut être définie pour des échantillons par pixel égal à 1 uniquement. ou Les bits par échantillon ne sont pas définis. |
| ArgumentOutOfRangeException | value;La longueur du tableau doit correspondre à la formule suivante : 3 * (2**BitsPerSample). |

### Voir également

* class [TiffOptions](../)
* espace de noms [Aspose.PSD.ImageOptions](../../tiffoptions/)
* Assemblée [Aspose.PSD](../../../)


