---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PattResourceData. Définit le tampon de pixels du motif et la taille cible, met à jour Width / Height et stocke les données pour l'enregistrement en utilisant le mode de compression par défaut 0."
type: docs
weight: 110
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Définit le tampon de pixels du motif et la taille cible, met à jour [`Width`](../width/) / [`Height`](../height/), et stocke les données pour l'enregistrement en utilisant le mode de compression par défaut (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | Pixels 32 bits au format `0xAARRGGBB`. |
| limites | Rectangle | Limites de pixels du motif. |

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | La longueur du tableau de pixels doit être égale à la zone des limites. |

### Voir aussi

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


