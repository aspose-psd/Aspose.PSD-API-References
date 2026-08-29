---
title: "GifOptions.DoPaletteCorrection"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété GifOptions. Obtient ou définit une valeur indiquant si la correction de palette est appliquée"
type: docs
weight: 40
url: /fr/net/aspose.psd.imageoptions/gifoptions/dopalettecorrection/
---
{{< psd/tize >}}
## GifOptions.DoPaletteCorrection property

Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Property Value

`true` si la correction de palette est appliquée ; sinon, `false`.

## Remarques

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source sont analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend un certain temps, cependant l'image résultante disposera de la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur.

### Voir aussi

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


