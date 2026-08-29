---
title: "RasterImage.SetPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "RasterImage méthode. Définit la palette de l'image"
type: docs
weight: 570
url: /fr/net/aspose.psd/rasterimage/setpalette/
---
{{< psd/tize >}}
## RasterImage.SetPalette method

Définit la palette de l'image.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | La palette à définir. |
| updateColors | Booléen | si elle est définie sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Voir aussi

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


