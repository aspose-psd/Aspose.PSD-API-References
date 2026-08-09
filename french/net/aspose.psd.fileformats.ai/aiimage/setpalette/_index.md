---
title: "AiImage.SetPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode AiImage. Définit la palette de l'image"
type: docs
weight: 200
url: /fr/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

Définit la palette de l'image.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | La palette à définir. |
| updateColors | Booléen | si elle est définie sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | Non implémenté |

### Voir aussi

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


