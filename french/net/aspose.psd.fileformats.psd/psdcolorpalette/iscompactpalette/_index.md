---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdColorPalette. Obtient une valeur indiquant si la palette est compacte"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Obtient une valeur indiquant si la palette est compacte.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` si la palette est compacte ; sinon, `false`.

## Remarques

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, ou en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Définir cette valeur sur true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent se produire, donc utilisez-le avec précaution.

### Voir aussi

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


