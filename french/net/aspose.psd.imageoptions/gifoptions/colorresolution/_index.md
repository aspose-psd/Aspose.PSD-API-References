---
title: "GifOptions.ColorResolution"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété GifOptions. Obtient ou définit la résolution couleur du GIF"
type: docs
weight: 30
url: /fr/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

Obtient ou définit la résolution de couleur du GIF.

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

La résolution couleur.

## Remarques

Résolution couleur - Nombre de bits par couleur primaire disponibles dans l'image originale, moins 1. Cette valeur représente la taille de l'ensemble de la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image originale disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette originale, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source.

### Voir aussi

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


