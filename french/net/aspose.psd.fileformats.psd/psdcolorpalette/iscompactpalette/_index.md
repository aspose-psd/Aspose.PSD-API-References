---
title: PsdColorPalette.IsCompactPalette
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdColorPalette propriété. Obtient une valeur indiquant si la palette est compacte.
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Obtient une valeur indiquant si la palette est compacte.

```csharp
public bool IsCompactPalette { get; }
```

### Valeur de la propriété

`vrai` si compact il palette; sinon,`FAUX`.

### Remarques

Palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible ou, en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon il y aura 2 entrées ^ BitsPerPixel et l'image réservera plus d'espace pour toutes les entrées de palette possibles . Définir cette valeur sur true et modifier les entrées de la palette peut entraîner une baisse des performances car un mouvement de données peut se produire, utilisez-la donc avec précaution.

### Voir également

* class [PsdColorPalette](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* Assemblée [Aspose.PSD](../../../)


