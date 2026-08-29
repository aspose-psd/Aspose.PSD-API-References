---
title: "Image.SetPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Image. Définit la palette de l'image"
type: docs
weight: 250
url: /fr/net/aspose.psd/image/setpalette/
---
{{< psd/tize >}}
## Image.SetPalette method

Définit la palette de l'image.

```csharp
public abstract void SetPalette(IColorPalette palette, bool updateColors)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | La palette à définir. |
| updateColors | Booléen | si elle est définie sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Voir aussi

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


