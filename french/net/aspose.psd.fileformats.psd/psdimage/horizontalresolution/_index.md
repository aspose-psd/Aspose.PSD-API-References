---
title: "PsdImage.HorizontalResolution"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "PsdImage propriété. Obtient ou définit la résolution horizontale en pixels par pouce de ce PsdImage"
type: docs
weight: 170
url: /fr/net/aspose.psd.fileformats.psd/psdimage/horizontalresolution/
---
{{< psd/tize >}}
## PsdImage.HorizontalResolution property

Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [`PsdImage`](../).

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

La résolution horizontale.

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


