---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété GifOptions. Obtient ou définit le ratio d'aspect du pixel GIF"
type: docs
weight: 90
url: /fr/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

Obtient ou définit le rapport d'aspect des pixels du GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

Le ratio d'aspect du pixel GIF.

## Remarques

Ratio d'aspect du pixel - Facteur utilisé pour calculer une approximation du ratio d'aspect du pixel dans l'image originale. Si la valeur du champ n'est pas 0, cette approximation du ratio d'aspect est calculée selon la formule : Ratio d'aspect = (Ratio d'aspect du pixel + 15) / 64 Le Ratio d'aspect du pixel est défini comme le quotient de la largeur du pixel sur sa hauteur. L'intervalle de valeurs de ce champ permet de spécifier le pixel le plus large de 4 :1 au pixel le plus haut de 1 :4 par incréments de 1/64. Valeurs : 0 - Aucune information de ratio d'aspect fournie. 1..255 - Valeur utilisée dans le calcul.

### Voir aussi

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


