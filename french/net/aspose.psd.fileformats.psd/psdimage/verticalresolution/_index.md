---
title: PsdImage.VerticalResolution
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage propriété. Obtient ou définit la résolution verticale en pixels par pouce de cePsdImage .
type: docs
weight: 260
url: /fr/net/aspose.psd.fileformats.psd/psdimage/verticalresolution/
---
## PsdImage.VerticalResolution property

Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`PsdImage`](../) .

```csharp
public override double VerticalResolution { get; set; }
```

### Valeur de la propriété

La résolution verticale.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | ressource ResolutionInfo introuvable et impossible de définir la résolution appropriée |

### Remarques

La valeur par défaut pour PSD est 72, donc si[`ResolutionInfoResource`](../../../aspose.psd.fileformats.psd.resources/resolutioninforesource/) n'a pas été trouvé, cette valeur est renvoyée.

### Voir également

* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)


