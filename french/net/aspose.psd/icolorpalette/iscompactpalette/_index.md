---
title: IColorPalette.IsCompactPalette
second_title: Référence de l'API Aspose.PSD pour .NET
description: IColorPalette propriété. Obtient une valeur indiquant si la palette compacte est utilisée.
type: docs
weight: 40
url: /fr/net/aspose.psd/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

Obtient une valeur indiquant si la palette compacte est utilisée.

```csharp
public bool IsCompactPalette { get; }
```

### Valeur de la propriété

`vrai` si la palette compacte est utilisée ; sinon,`FAUX`.

### Remarques

La palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible ou, en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon il y aura 2 entrées ^ BitsPerPixel et l'image réservera plus d'espace pour toutes les entrées de palette possibles. La définition de cette valeur sur true et la modification des entrées de la palette peuvent entraîner une baisse des performances car un mouvement de données peut se produire, utilisez-la donc avec précaution.

### Voir également

* interface [IColorPalette](../)
* espace de noms [Aspose.PSD](../../icolorpalette/)
* Assemblée [Aspose.PSD](../../../)


