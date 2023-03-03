---
title: GifOptions.ColorResolution
second_title: Référence de l'API Aspose.PSD pour .NET
description: GifOptions propriété. Obtient ou définit la résolution de couleur GIF.
type: docs
weight: 30
url: /fr/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
## GifOptions.ColorResolution property

Obtient ou définit la résolution de couleur GIF.

```csharp
public byte ColorResolution { get; set; }
```

### Valeur de la propriété

La résolution des couleurs.

### Remarques

Résolution des couleurs - Nombre de bits par couleur primaire disponible pour l'image d'origine, moins 1. Cette valeur représente la taille de la palette entière à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, la palette de l'image d'origine disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette d'origine, même si toutes les couleurs de l'ensemble de la palette ne sont pas disponibles sur la machine source.

### Voir également

* class [GifOptions](../)
* espace de noms [Aspose.PSD.ImageOptions](../../gifoptions/)
* Assemblée [Aspose.PSD](../../../)


