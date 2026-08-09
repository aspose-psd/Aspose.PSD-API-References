---
title: "PsdImage.VerticalResolution"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdImage. Obtient ou définit la résolution verticale en pixels par pouce de ce PsdImage"
type: docs
weight: 270
url: /fr/net/aspose.psd.fileformats.psd/psdimage/verticalresolution/
---
{{< psd/tize >}}
## PsdImage.VerticalResolution property

Obtient ou définit la résolution verticale, en pixels par pouce, de ce [`PsdImage`](../).

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

La résolution verticale.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Ressource ResolutionInfo non trouvée et impossible de définir la résolution correcte |

## Remarques

La valeur par défaut pour le PSD est 72, donc si [`ResolutionInfoResource`](../../../aspose.psd.fileformats.psd.resources/resolutioninforesource/) n'a pas été trouvé, cette valeur est renvoyée.

### Voir aussi

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


